using System.Collections;
using System.Collections.Generic;
using UnityEngine;
 
public class HelloWorld : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        //Вывод в консоль приветствия миру
        print("Hello, World!");
    }
 
    // Update is called once per frame
    void Update()
    {
 
    }
}


Crickets.cs

using System.Collections;
using System.Collections.Generic;
using UnityEngine;
 
public class Crickets : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
 
    }
 
    // Update is called once per frame
    void Update()
    {
        //Вывод в консоль слова «crickets»
        print("crickets");
    }
}
 

Destroy.cs 

using System.Collections;
using System.Collections.Generic;
using UnityEngine;
 
public class Destroy : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        //Уничтожение игрового объекта, к которому прикреплён скрипт
        Destroy(gameObject);
    }
 
    // Update is called once per frame
    void Update()
    {
 
    }
}

CreatePrimitives.cs 

using System.Collections;
using System.Collections.Generic;
using UnityEngine;
 
public class CreatePrimitives : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        //Создание фигуры Стива из Minecraft с помощью кубов
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(0, 0, 0);
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(-0.5f, 1, 0);
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(0.5f, 1, 0);
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(0.5f, 2, 0);
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(-0.5f, 2, 0);
        GameObject.CreatePrimitive(PrimitiveType.Cube).transform.position = new Vector3(0, 3, 0);
    }
 
    // Update is called once per frame
    void Update()
    {
 
    }
}
