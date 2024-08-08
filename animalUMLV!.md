```mermaid
    classDiagram

    class Animal{
        int numLegs
        String class
        String color
        hasTail boolean 
        eat()
        reproduce() 
        die()
    }


    class Zebra{
        trot()
        gallop()
        numStripes byte
    }


    Animal <|-- Zebra 

    class MountainZebra{
        mountainRange
        hillClimb()
    }


    