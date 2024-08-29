<!-- Centered top image -->
<p align="center">
  <img src="https://github.com/SpawnCampGames/Documentation/blob/main/gfx/SPWN.png" width="307" height="91" alt="SPWN Logo">
</p>

```csharp
using SPWN;
```
>[!IMPORTANT]
> Don't forget to include the **using** statement. ☝️

## 📗Dbug.cs

### String Interpolation for Variables
- To pass in variables to be logged use string interpolation.
```csharp
int myInteger = 2;
Dbug.Emphasis($"My Integer is: {myInteger}");
```

![Dbug String Interpolation](https://github.com/SpawnCampGames/Dbug/blob/main/img/DbugStringInterpolation.png)

---

### Navigating to Error
- To navigate to the actual script calling the log use the *stack trace* in the console.
- It will be presented as the very bottom (first) log.
- Instead of just double-clicking the log, double-click this link instead.

![Dbug Stack](https://github.com/SpawnCampGames/Dbug/blob/main/img/DbugStack.png)

### Included:

![Dbug Burn In](https://github.com/SpawnCampGames/Dbug/blob/main/img/DbugBurnIn.png)

#### Regular Logs
```csharp
Dbug.Log(msg);
Dbug.Warning(msg);
Dbug.Error(msg);
```
#### Colored Logs
```csharp
Dbug.Red(msg);
Dbug.Orange(msg);
Dbug.Yellow(msg);
Dbug.Green(msg);
Dbug.Blue(msg);
Dbug.Indigo(msg);
Dbug.Violet(msg);
```
#### Stylized Logs
```csharp
Dbug.Bold(msg);
Dbug.Italic(msg);
Dbug.Underline(msg);
Dbug.Strikethrough(msg);
```

#### Emphasized / Special Logs
```csharp
Dbug.Emphasis(msg);
Dbug.Test(msg);
Dbug.Physics(msg);
Dbug.Info(msg);
Dbug.Hit(msg);
```

#### Emphasized / Status Logs
```csharp
Dbug.Started(msg);
Dbug.Stopped(msg);
Dbug.Succeeded(msg);
Dbug.Failed(msg);
```

#### 🍦Chose your flavor.
> To create your own stylized log
```csharp
Dbug.MyLog(msg, #FFFFFF, false, false, false, false);
```
`msg, #hexcolor, bold, italic, underline, strikethrough`

---

### 📗DbugDiagnostic.cs
  
- Attach to GameObject
- Press **Play** / Run Game
- The DbugDiagnostic tool will cycle and call all Dbug functions.

> [!NOTE]
> Test Object Only.  
> Remove promptly

<!-- Start Whitespace /-->
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
<!-- End Whitespace /-->

<!-- Centered bottom image with scaling -->
<p align="center">
  <img src="https://github.com/SpawnCampGames/Documentation/blob/main/gfx/SpawnCampGames_DOC.png" width="300" alt="SpawnCampGames">
</p>
