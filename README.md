<div align="center">
	<img src="https://github.com/ashtonland/unity-ecs-snippets-for-visual-studio/assets/65512990/86931d20-8732-4875-a989-ed6595d1d5b0" alt="Logo" width="90" height="90">
	<h3 align="center">Unity ECS Snippets for Visual Studio</h3>
	<p align="center" max-width="100px">
    Official Visual Studio port of the Unity ECS Snippets vscode extension.
    <br />
    <br />
    <a href="https://github.com/ashtonland/unity-ecs-snippets"><strong>See in action »</strong></a>
   	<br />
  </p>
</div>
<br />
<p align="center">
<img width="800" src="https://github.com/ashtonland/unity-ecs-snippets/assets/65512990/664a39c7-59d1-425a-a48b-9f89a82b3f5d" />
</p>
<br />

| Command             |      Action      |
| :------------------- | :------------------- |
| dcs       |      Create a Unity DOTS System with the ISystem interface       |
| dcsss |     Create a Unity DOTS ISystem with onStartRunning & onStopRunning callbacks      |
| dcsb |     Create a managed Unity DOTS System with the SystemBase class      |
| dcc |     Create a Unity DOTS unmanaged component (recommended if using blittable types)      |
| dcmc |     Create a Unity DOTS managed component (only if using NON-blittable types)      |
| dcmcer |     Create a Unity DOTS managed component referencing an external resource      |
| dcsc |     Create a Unity DOTS unmanaged shared component (for components used on many entities & with the same values)      |
| dcmsc |     Create a Unity DOTS managed shared component (for shared components using non-blittable types)      |
| dcj |     Create a Unity DOTS Job (no `using Unity.Entities` added with this command, for it is likely added to a System file & not standalone)      |
| dcb       |      Create a Unity DOTS component baker & its authoring monobehavior class       |
| dcbd       |      Create a Unity DOTS component baker referencing another data source (i.e. mesh, gameObject, scriptable obj...)       |
| dca       |      Create a Unity DOTS aspect (used to group related components)       |
| dcrc       |      Create a Unity Physics (the DOTS package) raycast.      |

## Contributors
<a href="https://github.com/ashtonland">
  <img alt="Ashton Dev" src="https://avatars.githubusercontent.com/u/65512990?v=4" width="80" />
</a> 

## Also Download for VSCode
If you want to download this extension for VSCode in addition to this Visual Studio one to bring easier DOTS development to both code editors, you can download ECS Snippets for VSCode from the Marketplace [here](https://marketplace.visualstudio.com/items?itemName=ashtondev.unity-ecs-snippets).
