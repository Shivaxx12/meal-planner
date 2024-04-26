# The Digital Dietitian App/Portal Subject: Integrated Project (CS203) Session: Jan - Jun 2024

## Introduction:
Meal Planner Pro is a comprehensive online platform designed to revolutionize the way individuals approach meal planning. In today’s fast-paced world, maintaining a balanced diet can be challenging, often leading to unhealthy eating habits or reliance on convenience foods. Meal Planner Pro addresses these challenges by providing users with a customizable meal planning experience tailored to their unique preferences, dietary requirements, and health goals.

User Input Details:

#### Number of Meals:
 Users have the flexibility to choose the number of meals they wish to plan for, whether it’s three main meals a day or includes snacks in between.  This feature accommodates users with varying eating habits and schedules, ensuring that meal plans are personalized to meet their specific needs. 

#### 2. Plan Type:
 Meal Planner Pro offers two distinct plan types: weekly and daily.  Weekly plans provide users with a comprehensive overview of meals for the entire week, enabling them to prepare in advance and streamline grocery shopping.  Daily plans offer more detailed recommendations for each day, catering to users who prefer a day- by-day approach to meal planning.

#### 3. Dietary Preferences:
 Balanced Diet (Recommended): This option provides users with meal plans that prioritize a balance of carbohydrates, proteins, and fats, aligning with established nutritional guidelines for overall health and well-being.  Low-Carb (Less than 20% of total calories from carbs): Ideal for individuals following low-carb or ketogenic diets, this plan type emphasizes reduced carbohydrate intake while ensuring adequate protein and fat consumption.  Low-Fat (Less than 15% of total calories from fat): Suitable for those aiming to reduce fat intake, this plan focuses on meals with lower fat content while still providing essential nutrients and flavor.
#### 4. Health Preferences:
 Vegan (No meat, poultry, fish, dairy, eggs, or honey): This preference caters to individuals adhering to a vegan lifestyle, offering meal plans that exclude all animal-derived products while incorporating plant-based ingredients for nutrition and flavor.  Vegetarian (No meat, can have gluten though): Designed for vegetarians, this option excludes meat from meal plans but may include gluten-containing ingredients for variety and taste.  Alcohol-free (No alcohol used or contained): Ensures that meal recommendations do not include any alcoholic beverages or recipes containing alcohol, suitable for individuals abstaining from alcohol consumption.  Peanut Free (No peanuts or products containing peanuts): Addresses the needs of individuals with peanut allergies by excluding peanuts and peanut-containing products from meal plans to prevent allergic reactions.

#### 5. Calorie Intake:
 Recommended: Users can opt for meal plans based on standard recommended calorie intake guidelines, which are calculated based on factors such as age, gender, weight, height, and activity level.  Custom Daily Values: For users with specific calorie intake goals, this option allows them to input their desired daily calorie target, whether for weight loss, maintenance, or weight gain purposes.
Features:

#### Personalized Meal Plans: 
 Meal Planner Pro generates personalized meal plans based on the user’s input details, ensuring that each plan is tailored to their dietary preferences, health goals, and lifestyle.  Users receive a diverse selection of recipes for breakfast, lunch, dinner, and snacks, providing them with variety and flexibility in their meal choices.

#### Nutritionally Balanced Recommendations: 
 The platform emphasizes nutritionally balanced meal options, taking into account the user’s chosen diet type and health preferences.  Recipes are curated to meet recommended nutritional guidelines while incorporating a variety of ingredients and flavors to keep meals enjoyable and satisfying.

#### Interactive Interface: 
 Meal Planner Pro features an intuitive and user-friendly interface that allows users to easily navigate the platform and customize their meal plans.  Users can explore recipe details, adjust meal quantities, and make substitutions based on personal preferences or ingredient availability, enhancing the flexibility of the meal planning experience.

#### Shopping List Generation: 
 Each generated meal plan is accompanied by a comprehensive shopping list that itemizes the ingredients required for the recommended recipes.  Users can view, edit, and export the shopping list to their preferred format, making grocery shopping more efficient and convenient.

#### Recipe Exploration and Inspiration: 
 Meal Planner Pro offers a vast database of recipes spanning various cuisines, dietary preferences, and cooking skill levels.
 - A web application to plan what you eat daily in accordance to dietary needs. 
 - Please find the [demo here](https://arimai.github.io/meal-planner/#/).
 - This project was bootstrapped with [create-react-app](https://github.com/facebookincubator/create-react-app)
 - This project does not make use of any external CSS frameworks. Excuse the [sassiness](http://sass-lang.com/). :wink:
 - This project has been designed mobile-first and makes use of [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) extensively.

#### Technology tags
- React
- SASS
- Flexbox
- [Edamam](https://www.edamam.com/) recipe search API

#### Future Ideas
- Adding a grocery list aggregating all ingredients from the suggested meals
- Creating more selection criteria for health concerns such as PCOD, Diabetes, etc by collecting and analyzing data from several health and nutrition websites.
 
#### Project architecture
```
|-src
    |-components
      |-shared : All the components shared across the application
      |-page : Container components that serve as pages and use the shared components
    |-partials : Sass folder to include any partial sass files and a manifest file that imports all partials
    |-utils : Helper folder to contain any files that help the application, in this case, data fetching from the Edamam API
    |-App.js : The container component that decides how the app is navigated
    |-index.js : The JavaScript entry file 
    |-global.scss : Sass file that contains global application styles
```

#### Learnings through this project

- The Edamam API allows to query for recipes based on several parameters. However not all of them return apt results.
I had to tweak my survey form to include only those fields that successfully returned some results.
- Having components that don't require to maintain state should be written as stateless components. 
Some of the advantages of this approach is nicely discussed in [this](https://hackernoon.com/react-stateless-functional-components-nine-wins-you-might-have-overlooked-997b0d933dbc) article.
}

#### Made by Shivaksh, Vanshika, Anshika and Sakhib.
