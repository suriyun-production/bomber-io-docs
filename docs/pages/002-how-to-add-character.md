* * *

![](../images/11CARlGsibDu3O1egaKn93w.png)

This is the guide for Battle IO game template which selling at Unity Asset Store ([https://www.assetstore.unity3d.com/#!/content/102515?aid=1100lGeN](https://www.assetstore.unity3d.com/#!/content/102515?aid=1100lGeN))

First, prepare character model. You may create empty scene then drag your character model into the scene to manage it, In your character model add **CharacterModel** component

![](../images/0XIXW3v8e8TdU3UeV.png)

Then explore into character model children drag game object which you want to instantiate model to each container in **CharacterModel** component

![](../images/0oN5GfQBpGovQzWqB.png)

Then make it as a prefab.

Next, you have to create **CharacterData**, right click on anywhere in Project tab choose **Create -> ScriptableObject**

![](../images/0niPJMlcFzGHGB0_8.png)

In **Create ScriptableObject** dialog choose **CharacterData**

![](../images/0mFpKhoo2fIHUjj6e.png)

Then set it name as you wish but it must be unique for example I set it as **Character001**

Then in character data set **Character Model** to character model prefab that you have created

![](../images/0znhE-mCwemwH7Ft9.png)

Then open **Home** scene add character data to **GameInstance**

![](../images/0-fdIWhs6_p8W5Bfn.png)

![](../images/0BJ0RTIle7gG97odg.png)