# A simple code style example:
```
using System;
using UnityEngine;
namespace CodeStyleTemplate //It is necessary to write namespaces.
{  
    internal class Program
    {
        #region Public Variables

        // A const
        public const string CONST_VARIABLE = "CONST_VARIABLE";

        // A static
        public static int StaticVariable;

        // An event
        public event Action EventVariable;

        // A property
        public int PropertyVariable { get; set; }

        // A field
        public bool IsFieldVariable;

        #endregion
        #region [SerializeField] Private Variables

        // An event
        [SerializeField] private event UnityAction eventVariable;

        // A property
        [SerializeField] private int propertyVariable { get; set; }

        // A field
        [SerializeField] private bool isFieldVariable;

        #endregion
        #region Private Variables

        // A const
        private const string CONST_PRIVATE_VARIABLE = "CONST_VARIABLE";//like public

        // A static
        private static int _staticVariable;

        // An event
        private event Action _eventVariable;

        // A property
        private int _propertyVariable { get; set; }

        // A field
        private bool _isFieldVariable;

        #endregion

        // Method
        static void Main(string[] args)
        {
            //A local variable
            int localVariable;
        }
    }
}
```
