# Unity3D-homework1
* 游戏对象是指在游戏中出现的角色，NPC，场景环境等等。资源是用于装饰游戏对象的素材，可以修饰游戏对象的外观、纹理、动作和声音等等外部表现。

* 这是一个简易的俄罗斯方块游戏。<br/>
![](https://github.com/L1997YM/Unity3D-homework1/blob/master/tetrisL_gameobject.png)<br/>
Border对象有borderLeft和borderRight两个孩子,Canvas对象有Timer和Score两个孩子。<br/>
![](https://github.com/L1997YM/Unity3D-homework1/blob/master/tetrisL_assets.png)<br/>
Prefabs中有六块资源，用来修饰Border对象的形状，此外还有一些脚本文件。<br/>

* 
      using System.Collections;
      using System.Collections.Generic;
      using UnityEngine;

      public class NewBehaviourScript : MonoBehaviour {

        void Awake()
        {
           Debug.Log("Awake");
        }
        void Start () 
        {
           Debug.Log("Start");
        }
        void Update () 
        {
           Debug.Log("Update");
        }
        void FixedUpdate()
        {
           Debug.Log("FixedUpdate");
        }
        void LateUpdate()
        {
           Debug.Log("LateUpdate");
        }

        void OnGUI()
        {
           Debug.Log("OnGUI");
        }
        void OnDisable()
        {
           Debug.Log("OnDisable");
        }
        void OnEnable()
        {
           Debug.Log("OnEnable");
        }
      }
      
* 
  1. GameObject:Unity场景中所有实体的基类。<br/>
     Transform：对象的位置，旋转和缩放。<br/>
     Component：所有附加在游戏对象上的物品的基类。<br/>
  2. <br/>
    table的对象属性 <br/>
    Tag: Untagged <br/>
    Layer: Default <br/>
    Transform 的属性 <br/>
    Position: (0, 0, 0) <br/>
    Rotation: (0, 0, 0) <br/>
    Scale: (1, 1, 1) <br/>
    table的部件<br/>
    Transform,Cube(Mesh Renderer),Box Collider<br/>
