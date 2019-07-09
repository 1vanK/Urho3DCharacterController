# Urho3D Character Controller

## Литература

Алгоритм перешагивания неровностей, который используется практически везде: <https://www.gamasutra.com/view/feature/131508/bsp_collision_detection_as_used_in_.php?print=1>

### Serious Engine

<https://github.com/Croteam-official/Serious-Engine/blob/master/Sources/Engine/Classes/MovableEntity.es> > TryToGoUpstairs()

### Doom 3

<https://github.com/id-Software/DOOM-3/blob/master/neo/d3xp/physics/Physics_Player.cpp> > SlideMove()

### NVIDIA PhysX

#### Оригинальный Character Controller

* Документация: <https://docs.nvidia.com/gameworks/content/gameworkslibrary/physx/guide/Manual/CharacterControllers.html>
* Иерархия классов: <http://docs.nvidia.com/gameworks/content/gameworkslibrary/physx/apireference/files/classPxController.html>
* Исходник 3.4: <https://github.com/NVIDIAGameWorks/PhysX-3.4/tree/master/PhysX_3.4/Source/PhysXCharacterKinematic/src>
* Исходник 4.1: <https://github.com/NVIDIAGameWorks/PhysX/tree/4.1/physx/source/physxcharacterkinematic/src> (TODO: есть ли разница?)

#### Unity

Unity использует CC из PhysX (TODO: разобраться, модифицированный или оригинальный), однако
есть самописный на языке C#: <https://github.com/Unity-Technologies/Standard-Assets-Characters/blob/master/Assets/_Standard%20Assets/Characters/Scripts/Physics/OpenCharacterController.cs>

#### Torque 3D

<https://github.com/GarageGames/Torque3D/blob/development/Engine/source/T3D/physics/physx3/px3Player.cpp>

### Bullet Physics Library

* Оригинальный CC: <https://github.com/bulletphysics/bullet3/tree/master/src/BulletDynamics/Character>
* Torque 3D: <https://github.com/GarageGames/Torque3D/blob/development/Engine/source/T3D/physics/bullet/btPlayer.cpp>
* OpenMW: <https://gitlab.com/OpenMW/openmw/blob/master/apps/openmw/mwphysics/physicssystem.cpp>

### CryEngine
<https://github.com/CRYTEK/CRYENGINE/blob/release/Code/CryEngine/CryPhysics/livingentity.cpp> TODO: что-то мутный код, тут точно Character Controller?

### Unreal Engine

* Как получить доступ к официальному репозиторию: <https://github.com/EpicGames/Signup>
* <https://github.com/EpicGames/UnrealEngine/blob/release/Engine/Source/Runtime/Engine/Private/Components/CharacterMovementComponent.cpp> > MoveAlongFloor()
* <https://github.com/EpicGames/UnrealEngine/blob/release/Engine/Source/Runtime/Engine/Classes/GameFramework/CharacterMovementComponent.h>

### DigitalRune

* Документация: <https://digitalrune.github.io/DigitalRune-Documentation/html/7cc27ced-9a65-4ddd-8b8e-fa817b7fe6b7.htm>
* Исходник: <https://github.com/DigitalRune/DigitalRune/tree/master/Source/DigitalRune.Physics.Specialized/CharacterControllers>
