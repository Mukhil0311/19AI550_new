# Ex.No: 3  Basic movements in Unity 
### DATE: 26/10/2026                                                                           
### REGISTER NUMBER : 212225040263
### AIM: 
 To learn the basic movements translation,scaling and rotation of game objects through code.
### Procedure:
1. Setup the Scene
2. Open Unity and create a 3D Scene.
3. Add three objects:Cube → Rename to Object1 (for movement),Sphere → Rename to Object2 (for rotation).Capsule → Rename to Object3 (for scaling).
4. Add the Script,Create a C# Script → Name it TransformOperations.cs.
5. Write the code for translation,scaling and rotation,save and close the script
6. Save the script
7. Select any empty GameObject (or create one: GameObject → Create Empty).
8. Attach the TransformOperations script to it.
9. In the Inspector, assign Object1 → Drag the Cube,Object2 → Drag the Sphere.Object3 → Drag the Capsule.
10. Run the Scene Press Play ▶️ in Unity
11. Stop the program.
### Program 
```
sing UnityEngine;

public class Transformations : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    public Transform object1;
    public Transform object2;
    public Transform object3;
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        if (Input.GetKeyDown(KeyCode.X))
        {
            object1.Translate(2f, 0, 0);
        }
        if (Input.GetKeyDown(KeyCode.Y))
        {
            object2.Rotate(0, 10f, 0);
        }
        if (Input.GetKeyDown(KeyCode.Z))
        {
            object3.localScale += new Vector3(2f, 2f, 2f);
        }
    }

}

```
### Output:

<img width="1920" height="1080" alt="Screenshot 2026-10-26 185418" src="https://github.com/user-attachments/assets/2ab41a81-7985-483d-9fed-c368ff08d456" />




<img width="1920" height="1080" alt="Screenshot 2026-10-26 185410" src="https://github.com/user-attachments/assets/4c3e9efe-b440-44a2-9726-f6aa40eec7fe" />




### Result:
Thus the basic movement is learned through scripting


