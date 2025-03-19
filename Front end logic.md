Frontend is where is made the interface that the user will interact.

- A good example is a website page, it has their buttons, scrolls to navigate and menu.
- It differs from backend

Important things to remember
- Frontends have an architecture that is built through its components: Atoms, Molecules and organism
> Atoms are the smallest component (i.e buttons, scrolls, containers)
> Molecules are interactions between atoms, they can be useful to avoid repeating yourself, following the DRY (Don't repeat yourself) good practice

**Code structure**

*For typeScript and React*
Code:

import

export function name()
  return (
    <>
      <Container
        classname ={???}
        >
        <Sidebar props props> {/*props are part of the component that can be put in the atom that you are evoking */}
        <container classname = "settings settings settings" {/* settings are used to define lenght, height and other caracteristics*/
          <div classname="settings for div"> {/*classnames set ups settings for the div and it will be applied for all containers within the div  */}
            <container props props>
              text
            </container>
            <container classname="settings settings settings")
            <p>
            text text
            </p>
            <br>
            <p>
             text
            </p>
            </container> {/*This one closes the container before, it's important to notice that all open components expect to be closed */}
          </div>
        <container>
      <container>
  <>
)
