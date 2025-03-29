**Design System**

- Objective: Used to organize components that carries functions that can be imported in files to build a page or another feature in example.
- It remains the repository organized, since you can import the function/component many times in different files instead of creating functions everytime or creating it everytime in files.

  Example:
  For react, there is a framework based on: Atoms, molecules and organism.
  - Atoms are a single function structure
   Example:
    https://github.com/Coletivo-Anarquista-Trans/site/blob/dev/src/components/atoms/CyberContainer/index.tsx
    
  - Molecules are functions made using atoms components
   Example:
    https://github.com/Coletivo-Anarquista-Trans/site/blob/dev/src/components/molecules/CyberImage/index.tsx
  
  - Organism are made from molecules
   Example:
    https://github.com/Coletivo-Anarquista-Trans/site/tree/dev/src/components/organism
 
Example of components architecture: https://github.com/Coletivo-Anarquista-Trans/site/tree/dev/src/components

**How to use it**

1. When working in a file you can import the components by using:
import componentName "from @/path";

2. When doing this your file will import the component and then the function in the component will be available to use it on the code
 
There is many other frameworks that we may discover while learning coding. :3
    
