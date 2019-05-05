* * *

![](../images/11CARlGsibDu3O1egaKn93w.png)

This is the guide for Battle IO game template which selling at Unity Asset Store ([https://www.assetstore.unity3d.com/#!/content/102515?aid=1100lGeN](https://www.assetstore.unity3d.com/#!/content/102515?aid=1100lGeN))

First, prepare bomb entity. You may create empty scene then drag your bomb model into the scene to manage them, In the bomb model add **Bomb Entity** component

![](../images/0epaAdBrrTQGqZAxv.png)

In the bomb entity you can set

*   **Explosion Sound** it is the sound which will play when bomb explode
*   **Explosion Effect** it is the fire effect which will play each cells its size should be fit to the cell (x=1, y=1 z=1), you can use particle system to make it as fire effect and you have to attach **EffectEntity** component to the particles you have created
*   **Life Time** it is delay before it explode

After finished setup then make them as prefab you will use it to set in **BombData**

![](../images/0R84hnV4q0i8Bow-u.png)

Next, you have to create **BombData**, right click on anywhere in Project tab choose **Create -> ScriptableObject**

![](../images/057TrawcSkgC64zCO.png)

In **Create ScriptableObject** dialog choose **BombData**

![](../images/0tSA-jqrH7BPutlbN.png)

Then in bomb data set bomb entity prefabs that you have created

![](../images/0fMLrPAzMQy8KrTPi.png)

Then open **Home** scene add bomb data to **GameInstance**

![](../images/0popr0mKdx8tx2dp6.png)

![](../images/0WEjVIGElSExJN_VD.png)