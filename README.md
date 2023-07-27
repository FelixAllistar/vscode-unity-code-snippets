# Unity Code Snippets

Create Unity classes and methods easily.

![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/kleber-swf.unity-code-snippets?color=red&style=for-the-badge)
![Visual Studio Marketplace Rating (Stars)](https://img.shields.io/visual-studio-marketplace/stars/kleber-swf.unity-code-snippets?color=blue&style=for-the-badge)
![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/kleber-swf.unity-code-snippets?color=orange&style=for-the-badge)

## Features

> **2.0.0**: Support to style configuration. Now you can use [K&R](https://en.wikipedia.org/wiki/Indentation_style#K&R_style) and [Allman (C#/Unity default)](https://en.wikipedia.org/wiki/Indentation_style#Allman_style) styles! More at [Configuration](#configuration) section.

All the Unity code snippets you need. This extension intends to be the complete collection of Unity snippets for Visual Studio Code.

It takes advantage of latest Visual Studio Code snippets features to create the code faster for you.

### MonoBehaviour

Create game classes like `MonoBehaviours`, `NetworkBehaviours` and `StateMachineBehaviours` easily. Also create common methods like `Start()`, `Update()` or `OnTriggerEnter2D()` and log calls.

![MonoBehaviour](https://raw.githubusercontent.com/kleber-swf/vscode-unity-code-snippets/master/images/usage-01.gif)

### Editor

Create Editor classes like `Editor`, `EditorWindow` and `PropertyDrawer` as easy as it can be.

![Unity Editor](https://raw.githubusercontent.com/kleber-swf/vscode-unity-code-snippets/master/images/usage-02.gif)

### ScriptableObject

You never remember the property that goes with the `ScriptableObject` to create it via Unity create menu? Not a problem.

![ScriptableObject](https://raw.githubusercontent.com/kleber-swf/vscode-unity-code-snippets/master/images/usage-03.gif)

## Installation

As in any Visual Studio Code Extension you have several options to install:

-  Enter the Visual Studio Code Marketplace, search for _Unity Code Snippets_ (or enter directly on [the extension page](https://marketplace.visualstudio.com/items?itemName=kleber-swf.unity-code-snippets)) and click on _Install_ button.
-  Inside Visual Studio Code, enter in the Extensios panel, search for _Unity Code Snippets_ and click on _Install_ button
-  Run the following command in the Command Palette:
   ```
   ext install kleber-swf.unity-code-snippets
   ```

## Configuration

Starting at version `2.0.0` the extension is configurable.

> For now you can just change the indentation/formatting style to K&R or Allman, but there are plans for the future to make the extension more flexible.

To configure the extension, open VSCode Settings and search for "Unity Code Snippets".

Available options:

-  `style`: The [indentation style](https://en.wikipedia.org/wiki/Indentation_style) for the snippets. For now you can choose between [K&R Style](https://en.wikipedia.org/wiki/Indentation_style#K&R_style) (the default for 1.x version) and [Allman Style](https://en.wikipedia.org/wiki/Indentation_style#Allman_style) (default to C#/Unity). After changing this option, you need to restart VSCode.

## All the snippets

Start typing the names to create the corresponding snippets.

-  Game classes:

   -  `MonoBehaviour`
   -  `StateMachineBehaviour`
   -  `NetworkBehaviour`
   -  `ScriptableObject`

-  Editor Classes:

   -  `Editor`
   -  `Editor with Reorderable List` **_(NEW)_**
   -  `EditorWindow`
   -  `PropertyDrawer`
   -  `ScriptableWizard`

-  MonoBehaviour Methods/Fields:

   -  `Awake()`
   -  `FixedUpdate()`
   -  `LateUpdate()`
   -  `OnAnimatorIK()`
   -  `OnAnimatorMove()`
   -  `OnApplicationFocus()`
   -  `OnApplicationPause()`
   -  `OnApplicationQuit()`
   -  `OnAudioFilterRead()`
   -  `OnBecameInvisible()`
   -  `OnBecameVisible()`
   -  `OnCollisionEnter()`
   -  `OnCollisionEnter2D()`
   -  `OnCollisionExit()`
   -  `OnCollisionExit2D()`
   -  `OnCollisionStay()`
   -  `OnCollisionStay2D()`
   -  `OnConnectedToServer()`
   -  `OnControllerColliderHit()`
   -  `OnDestroy()`
   -  `OnDisable()`
   -  `OnDisconnectedFromServer()`
   -  `OnDrawGizmos()`
   -  `OnDrawGizmosSelected()`
   -  `OnEnable()`
   -  `OnFailedToConnect()`
   -  `OnFailedToConnectToMasterServer()`
   -  `OnGUI()`
   -  `OnJointBreak()`
   -  `OnJointBreak2D()`
   -  `OnMasterServerEvent()`
   -  `OnMouseDown()`
   -  `OnMouseDrag()`
   -  `OnMouseEnter()`
   -  `OnMouseExit()`
   -  `OnMouseOver()`
   -  `OnMouseUp()`
   -  `OnMouseUpAsButton()`
   -  `OnNetworkInstantiate()`
   -  `OnParticleCollision()`
   -  `OnParticleTrigger()`
   -  `OnPlayerConnected()`
   -  `OnPlayerDisconnected()`
   -  `OnPostRender()`
   -  `OnPreCull()`
   -  `OnPreRender()`
   -  `OnRenderImage()`
   -  `OnRenderObject()`
   -  `OnSerializeNetworkView()`
   -  `OnServerInitialized()`
   -  `OnTransformChildrenChanged()`
   -  `OnTransformParentChanged()`
   -  `OnTriggerEnter()`
   -  `OnTriggerEnter2D()`
   -  `OnTriggerExit()`
   -  `OnTriggerExit2D()`
   -  `OnTriggerStay()`
   -  `OnTriggerStay2D()`
   -  `OnValidate()`
   -  `OnWillRenderObject()`
   -  `Reset()`
   -  `Start()`
   -  `Update()`
   -  `[SerializeField]`

-  Debug class

   -  `Debug.DrawLine()`
   -  `Debug.DrawRay()`

-  Some useful code snippets:
   -  `Debug.Log()` (type _`log`_)
   -  `Debug.LogError()` (type _`logerror`_)
   -  `Debug.LogWarning()` (type _`logwarning`_)
   -  `Debug.LogException()` (type _`logexception`_)

If you have any suggestions, [open an issue in the Github project](https://github.com/kleber-swf/vscode-unity-code-snippets/issues) page and I'll add them as soon as I can :).

If you like the color theme of the previews, you can download it here: [Base16 Ocean Dark Extended Theme](https://marketplace.visualstudio.com/items?itemName=kleber-swf.ocean-dark-extended).

Thank you for downloading this extension.
