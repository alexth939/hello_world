## `DayTimeManager`

```csharp
public class DayTimeManager
    : MonoBehaviour

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Single` | acceleratedTimeScale |  | 
| `String` | finishWorkTimeString |  | 
| `String` | startWorkTimeString |  | 
| `Boolean` | timeAcceleration |  | 
| `DateTime` | workTime |  | 


## `FieldOfView`

```csharp
public class FieldOfView
    : MonoBehaviour

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | CanSeePlayer |  | 
| `Single` | lookingAngle |  | 
| `Single` | lookingDistance |  | 
| `LayerMask` | obstructionLayer |  | 
| `GameObject` | playerRef |  | 
| `LayerMask` | targetLayer |  | 


## `InteractiveObject`

```csharp
public class InteractiveObject
    : MonoBehaviour

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Boolean` | destroyAfter |  | 
| `Single` | secondsForCompleting |  | 
| `Boolean` | withTimeAcceleration |  | 


## `InventoryManager`

```csharp
public class InventoryManager
    : MonoBehaviour

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `List<InventoryItem>` | items |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | CollectItem(`Item` item, `Int32` count) |  | 
| `Int32` | GetCount() |  | 
| `void` | GetItemGraphics(`Int32` id, `Sprite&` itemSprite, `Int32&` itemCount) |  | 
| `Int32` | GetSelectedCellID() |  | 


## `InventoryUI`

```csharp
public class InventoryUI
    : MonoBehaviour

```

## `Item`

```csharp
public class Item
    : ScriptableObject

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `String` | description |  | 
| `Sprite` | itemImage |  | 
| `String` | itemName |  | 
| `ItemType` | itemType |  | 
| `Int32` | maxCount |  | 
| `GameObject` | physicalObject |  | 


## `ItemObject`

```csharp
public class ItemObject
    : MonoBehaviour

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Item` | item |  | 


## `SleepBar`

```csharp
public class SleepBar
    : MonoBehaviour

```

## `Task`

```csharp
public class Task
    : ScriptableObject

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Int32` | officeNumber |  | 
| `List<TaskStep>` | taskSteps |  | 


## `TaskManager`

```csharp
public class TaskManager
    : MonoBehaviour

```

Fields

| Type | Name | Summary | 
| --- | --- | --- | 
| `Int32` | maxCountSelectedTasks |  | 


Methods

| Type | Name | Summary | 
| --- | --- | --- | 
| `void` | CheckInteractionWithObject(`InteractiveObject` interactiveObject) |  | 
| `void` | CheckInteractionWithObject(`InteractiveObject` interactiveObject, `InventoryItem` item) |  | 
| `void` | CheckTaking(`List<InventoryItem>` inventoryItems) |  | 
| `void` | GetNewTask(`Task` task) |  | 


## `TimeTests`

```csharp
public class TimeTests
    : MonoBehaviour

```

## `Waypoint`

```csharp
public class Waypoint
    : MonoBehaviour

```

## `WorkTime`

```csharp
public class WorkTime
    : MonoBehaviour

```

