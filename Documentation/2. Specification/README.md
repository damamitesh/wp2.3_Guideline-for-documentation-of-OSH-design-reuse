# **Specification**

*The specification consists in describing the product with a "black box" external view to capture the intermediate technical objects (stakeholders, external interfaces, services, and constraints) that serve to, *in fine*, elucidate the product requirements.*

## **How to document the specifications?** 

## **1. Stakeholders:**

- **Definition:** *Stakeholders generally refer to all the actors (human and non-human) who have an interest in a product. Among the stakeholders, there are both internal players, such as users and participants of the project, and external players that are represented by the potential user of products or external entities.*

- **Comments:**

  - *A stakeholder is not necessarily a person (e.g. considering airports as a stakeholder when designing a two-deck aircraft).*
  - *A stakeholder can indirectly affect the product (e.g. considering neighborhood when designing a nuclear power plant).*
  - *A stakeholder can indirectly be affected by the product (e.g. considering the local biodiversity when designing an airport).*

  ```
  1. What entities influence the product throughout its life cycle ?
  
  - Stakeholder name 1
  - Stakeholder name 2
   - ...
  
  ```

## **2. External interfaces**

- **Definition:**  *External interfaces are interactions between the product and the stakeholders.*

- **Comments:**
  - *An interface is made of a port (in, out, or in-out)*
  - *An interface is made of a flow (matter, energy, or signal)*
  
 ```
External interfaces consistits:

  - Stakeholder name 1
    - Flow 1
    - Flow 2
    - ...
  - Stakeholder name 2
    - Flow 1'
    - Flow 2'
    - ...
  ```

## 3. Service *(synonyms: external function, capability)* 

- **Definition:** *A service is an effect intended by a stakeholder resulting from the interaction of the product with its environment (i.e. what the  product is for).*

- **Comments:**
  - *Services provides users with and exchange value that can be included in an economic system (e.g. airlines buy flight hours).*
  - *Services are intended effects that can observed from outside the product ("back box" external view), but not from outside an internal component ("white box" internal view).*
  - *Services are defined in a solution neutral way.*
  - *Services can be stated as follows : The [Product] shall enable [Stakeholder] [Action verb] (e.g. The product shall enable end-user to clean its teeths)*
  
 ```
  Action verb (we often reason in terms of action verbs to communicate expected behaviours, so it would be nice to be able to search designs with action verbs)
  
  Services to stakeholders includs:
  
    - Services to stakeholder 1
      - Service 1.1:...
      - Service 1.2:...
      - ...
    - Services to stakeholder 2
      - Service 2.1:...
      - Service 2.2:...
      - ...
    - ...
  ```
  
## 4. Constraint *(Synonyms: non function requirement)*

- **Definition:**  *A constraint is a choice that makes certain designs "not allowed" or inappropriate for its intended use.*

- **Comments:**

  - *Constraint is a restriction, limit, or regulation imposed on a product.*
  - *There are two kinds of constraints: input constraints and system constraints.* 
    - *Input constraints are imposed as part of the design specifications.*
    - *System constraints are constraints imposed by the system in which the design solution must function.*
    
 
   ```
  Documentation of imposed constraints on the productcontain:
  
   - Constraint 1:...
   - Constraint 2:...
   - Constraint 3:...
   - ...
  ```

## **5. Requirement**

- **Definition:** *A requirement is a formal statement that specifies when condition C is true, property P of object O is actual and its value shall belong  to domain D.*

- **Comments:**
  -  *The minimum set of independent requirements can completely characterize the needs of the product in the functional domain.*
  -  *Functional requirement describe qualitatively the system functions or tasks to be performed in operation.* 
  -  *Requirement can state as follows: The [stakeholder] need [Property] [object] [Action verb]  at [Condition]* 
  
  ```
  Documebtaion of requirements include:
  
    - Requirement 1:...
    - Requirement 2:...
    - Requirement 3:...
      - ...
  ```
### Template
<details>
  <summary>Click to expand!</summary>
  
  1. Stakeholders
     * Stakeholder name 1
     * ...
  
  2. External interfaces
     * Stakeholder name 1
       * Flow 1
       * ...
    
  3. Service
     * Services to stakeholder 1
       * Service 1.1
       * ...
  
  4. Constraint
     * Constraint 1
     * ...
       
  5. Requirement
     * Requirement 1
     * ...
  
</details>
