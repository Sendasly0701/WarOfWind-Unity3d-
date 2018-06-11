# WarOfWind-Unity3d-
This program is use Unity3d and c sharp development, about a demo game as ARPG.
Demo video link < https://www.bilibili.com/video/av24530331 >, but this demonstration don't have Start UI.
Demo project download link < https://pan.baidu.com/s/1kxbq9Gs62zmJ6e8LkTiwdQ >.
Model and MapModel are be from Untiy AssetStore , Animat are be from Mixamo. Thanks developer very much.

Program code be split into three folders. Enemy, Player, CameraAndView.

Player's control are use Unity Animation System, first write PlayerInput, and use Rigidbody move in FixedUpdate.
FSM  certain render animat repetition call.

Enemy AI are use Ray and Unity NavMeshAgent to write. give Player tag and estimate RayHit are Player or barrier.
EnemyToPlayerDirection = Player.transform.position - Enemy.transform.position;
if this Direction.Distance < We set flaot, use NavMeshAgent to move of run to Player, and start attack animat.

This camera code are for learn in UnityCameraCodePackAge.

In this demo project let me konw develop is hard and loneliness, late time I will to learn basis of computer engineering.

Thanks watching for you.
