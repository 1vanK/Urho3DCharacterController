# Urho3D Character Controller

## Литература

### NVIDIA PhysX

#### Оригинальный Character Controller

1. Документация: <https://docs.nvidia.com/gameworks/content/gameworkslibrary/physx/guide/Manual/CharacterControllers.html>
2. Иерархия классов: <http://docs.nvidia.com/gameworks/content/gameworkslibrary/physx/apireference/files/classPxController.html>
3. Исходник 3.4: <https://github.com/NVIDIAGameWorks/PhysX-3.4/tree/master/PhysX_3.4/Source/PhysXCharacterKinematic/src>
4. Исходник 4.1: <https://github.com/NVIDIAGameWorks/PhysX/tree/4.1/physx/source/physxcharacterkinematic/src> (TODO: есть ли разница?)

#### Unity

Unity использует CC из PhysX (TODO: разобраться, модифицированный или оригинальный), однако
есть самописный на языке C#: <https://github.com/Unity-Technologies/Standard-Assets-Characters/blob/master/Assets/_Standard%20Assets/Characters/Scripts/Physics/OpenCharacterController.cs>

### Bullet Physics Library

1. Оригинальный CC: <https://github.com/bulletphysics/bullet3/tree/master/src/BulletDynamics/Character>
2. Torque 3D: <https://github.com/GarageGames/Torque3D/blob/development/Engine/source/T3D/physics/bullet/btPlayer.cpp>
3. OpenMW: <https://gitlab.com/OpenMW/openmw/blob/master/apps/openmw/mwphysics/physicssystem.cpp>
