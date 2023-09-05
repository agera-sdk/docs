# Entity-Component-System

Simulations and user interface are expressed using the **E**ntity-**C**omponent-**S**ystem (**ECS**) programming paradigm.

- **Components** can be assigned to an **entity**.
- A **system** operates on a world or set of user interface controls.
- Children entities allow for hierarchy, common for user interface controls. They also inherit certain components from the parent entity.

The Purplelight platform uses a third-party dependency for the Entity-Component-System pattern, [Bevy](https://bevyengine.org), but this section covers it all.