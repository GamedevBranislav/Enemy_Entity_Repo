Enemy from my 2D platformer with State Machine.
Entity have "Animator" "Rigidbody2D" and "EntityFX" components which Enemy Inheritence.
Enemy "Skeleton" in this case have 4 Stances Idle,Move,Battle,Attack.
He is moving and when he reach corner play Idle animation and then flip and move to the other direction.
When player is less distance then "attackDistance" which is 2f, then Enemy will change state to AttackState, 
if he cannot reach player or player left from his sight then after 12sec. he will come back to MoveState.

![EnemySkeleton](https://github.com/user-attachments/assets/4c358a40-34d3-47e9-86e1-4dc95a42334f)
