
```mermaid
usecase-beta
direction LR
actor user("User")
actor irrigation("Irrigation Pump")
systemBoundary "Sprout"
    visualize("Visualize Greenhouse State")
    configure("Configure System")
    control("Control Irrigation")
end
user --> visualize
user --> configure
user --> control
control --> irrigation
```