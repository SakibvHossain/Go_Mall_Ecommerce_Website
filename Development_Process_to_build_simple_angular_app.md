## Development Process  
![development_Process](https://github.com/SakibvHossain/Go_Mall_Ecommerce_Website/assets/92059000/8b32bcc2-f6df-40d5-a206-c1142469f9c8)

### 1. Create a new project
`ng new sales-project`  

### 2. Update main template page
Remove angular all the placeholders. Just add a basic HTML header `<h1> Sales Team </h1>`  

### 3. Generate new components
`ng generate component sales-person-list`  

### 4. Add new component selector to app template page
```
<h1> Sales Team </h1>
<app-sales-person-list> </app-sales-person-list>
```
Later on we will add html template here: `<p> sales-person-list works! </p>`  

### 5. Generate a sales person class
`ng generate class sales-person-list/SalesPerson` It will generate an empty class but we will modify to add some property like this:  
```
export class SalesPerson{
    constructor(public firstName: string,
                public lastName: string,
                public email: string,
                public salesVolume: number){
    }
}
```
### 6. In SalesPersonLisComponent create sample data
![sample data](https://github.com/SakibvHossain/Go_Mall_Ecommerce_Website/assets/92059000/9d9d9d31-59e7-45a3-ba49-ca951ce46922)

### 7. In sales-person-list template file, build HTML table by looping over the data
![wrapup with the data](https://github.com/SakibvHossain/Go_Mall_Ecommerce_Website/assets/92059000/4405f98b-12de-4327-8b7e-3df9099a13cc)

