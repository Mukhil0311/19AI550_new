# Ex.No: 2  Welcome Script in Unity
### DATE: 26/10/2026                                                                           
### REGISTER NUMBER : 212225040263
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        print("Hello World");
    }
}
```
### Output:

<img width="1920" height="1080" alt="Screenshot 2026-10-26 184854" src="https://github.com/user-attachments/assets/ff529f98-b83a-4bfb-a6bc-c74f82b1bedc" />

<img width="1920" height="1080" alt="Screenshot 2026-10-26 184830" src="https://github.com/user-attachments/assets/1866725d-666f-40f7-9c2a-7d5e0263e85e" />


### Result:
Thus the welcome script was printed on Console Window  sucessfully.

