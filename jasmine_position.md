# 座標系

```uml
@startuml

class SatellitePosition {
  + x
  + y
  + z
  + vx
  + vy
  + vz
  + to_heliocentric(date_time):HeliocentricPosition
}
@enduml
```
