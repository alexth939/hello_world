## `Clock`

```csharp
public class Runtime.Services.ForScene.Clock
    : IClock, ISceneService, IDisposable

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `ClockTime` | CurrentTime |  | 
| `Boolean` | IsRunning |  | 


Events

| Type | Name | Summary | 
| --- | --- | --- | 
| `TickEvent` | OnTick |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | AddTransientEvent(`ClockTime` timeTrigger, `Action` action) |  | 
| `void` | Dispose() |  | 
| `void` | Finalize() |  | 
| `void` | Run() |  | 
| `void` | Stop() |  | 


## `ClockTime`

```csharp
public struct Runtime.Services.ForScene.ClockTime

```

Properties

| Type | Name | Summary | 
| --- | --- | --- | 
| `Int32` | Hour |  | 
| `Int32` | Minute |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | AddHours(`UInt32` hours) |  | 
| `void` | AddMinutes(`UInt32` minutes) |  | 
| `Boolean` | Equals(`Object` obj) |  | 
| `Int32` | GetHashCode() |  | 
| `String` | ToString() |  | 


Static Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | IsValidFormat(`String` time) |  | 
| `Boolean` | IsValidValues(`Int32` hour, `Int32` minute) |  | 
| `ClockTime` | Lerp(`ClockTime` a, `ClockTime` b, `Single` t) |  | 
| `ClockTime` | Parse(`Int32` hour, `Int32` minute) |  | 
| `ClockTime` | Parse(`String` text) |  | 
| `Boolean` | TryParse(`String` text, `Nullable`1&` time) |  | 


## `ClockView`

```csharp
public class Runtime.Services.ForScene.ClockView
    : MonoBehaviour, IClockView

```

## `IClockView`

```csharp
public interface Runtime.Services.ForScene.IClockView

```

Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | SetTime(`ClockTime` time) |  | 


