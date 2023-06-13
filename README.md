# World Happiness Score
The creation of a basic application using React and react-globe.gl. The app utilizes Three.js for visualizing global happiness and other related social data. It is based on the example provided by react-globe.gl. If you're interested, I recommend checking out react-globe.gl for more information. [here](https://github.com/vasturiano/react-globe.gl).

# About the dataset
The World Happiness Report, published by the United Nations Sustainable Development Solutions Network, features articles and rankings that assess national happiness. The rankings are determined by individuals' self-assessment of their own lives and are correlated with different factors related to quality of life. As of March 2022, Finland has consistently been ranked as the happiest country in the world for five consecutive times.

The main data source for the report is the Gallup World Poll. Each year's report can be freely downloaded from the World Happiness Report website. The 2020 report was edited by John F. Helliwell, Richard Layard, Jeffrey D. Sachs, and Jan-Emmanuel De Neve, with Lara Aknin, Shun Wang, and Haifang Huang serving as Associate Editors. Source : [Wikipedia](https://en.wikipedia.org/wiki/World_Happiness_Report)

>NOTE: Certain Data Points [in the dataset](https://www.kaggle.com/datasets/shivkumarganesh/world-happiness-report-20152022) are available for Certain Years and others are not. While you may come across numerous columns with a significant amount of missing data, I have developed a straightforward Java program to handle and merge the necessary information for plotting and displaying the report on a map. This program compiles the data into a JSON file, allowing you to review and make more refined modifications as needed. [here](https://github.com/YohannesTz/JavaDataManuplater.git).

# Preivew
![preview](/globe-preview.png)

[Live Preview](https://world-happines-score.netlify.app/) [Video Preview](https://youtu.be/4gncZzITIiY)

## Available Scripts

In the project directory, you can run:

### `yarn start`

Launches the application in development mode.
Access http://localhost:3000 to view it in your browser.

The page will automatically refresh whenever you make modifications.
Additionally, any lint errors will be displayed in the console.

### `yarn test`

Activates the test runner in an interactive watch mode.


### `yarn build`

Compiles the application for production and generates the output in the build folder.
It appropriately packages React in production mode and optimizes the build for optimal performance.

The resulting build is minimized, and the filenames include unique hash values.
Your application is now prepared for deployment!

### `yarn eject`

**Note: Please note that this action is irreversible. Once you choose to "eject," it is not possible to revert the changes.**

If you find the build tool and configuration choices unsatisfactory, you have the option to "eject" at any time. This action will eliminate the single build dependency from your project.

Instead, it will duplicate all the configuration files and their associated dependencies (such as webpack, Babel, ESLint, etc.) directly into your project, granting you complete control over them. All commands, except for "eject," will continue to function, but they will refer to the duplicated scripts, allowing you to customize them according to your needs. From this point onward, you will be responsible for managing these configurations.

It's worth noting that using the "eject" feature is not obligatory. The curated set of features provided is suitable for small and medium deployments, and you should not feel compelled to utilize this option. Nevertheless, we recognize the importance of customization, and thus offer this capability when you are ready for it.
