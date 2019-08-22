using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace CStuff
{
    class Program
    {


        //@author Cameron Gibson

       
            public static void Main(string[] args)
            {
                Animal frog = new Amphibian("Frog", 2, "Red");
                Animal toad = new Amphibian("Toad", 4, "Green");
                Console.WriteLine(frog.ToString());
                Console.WriteLine(toad.ToString());
                Console.Read();
            }
        }
    }

    class Animal
    {

        public string species { protected get; set; }
        public int age { protected get; set; }

        public Animal()
        {

        }

        public Animal(string species, int age)
        {
            this.species = species;
            this.age = age;
        }

        public virtual string ToString()
        {
            return "SPECIES: " + species + "/tAGE: " + age;
        }
    }

    class Amphibian : Animal
    {

        public string skinColor { protected get; set; }

        public Amphibian()
        {

        }

        public Amphibian(string species, int age, string skinColor) : base(species, age)
        {
            this.skinColor = skinColor;
        }

        public override string ToString()
        {
            return "SPECIES: " + species + "\nAGE: " + age + "\nSKIN COLOR: " + skinColor;
        }
    }
