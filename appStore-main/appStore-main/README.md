In this project, I've built an **App Store** by implementing react component and component private property state.

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/app-store-sm-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/app-store-lg-output-v2.png)

</details>


<details>
<summary>Functionalities added</summary>
<br/>

The app has the following functionalities

- Initially, the **Social** tab will be active and the apps with **Social** as their category will be displayed
- When a value is provided in the search input
  - The apps in the active category, that include search input value in their name will be displayed
  - When another tab is clicked, the apps in the corresponding category, that include search input value in their name will be displayed
  - The search is insensitive
- When the search input is empty,
  - All the apps in the active category will be displayed
  - When another tab is clicked, the apps in the corresponding category will be displayed
- The `AppStore` component contains  a  `tabsList`. It consists of a list of tabItem objects with the following properties in each tabItem object

  |     Key     | Data Type |
  | :---------: | :-------: |
  |    tabId    |  String   |
  | displayText |  String   |

- The `AppStore` component contains a `appsList`. It consists of a list of app objects with the following properties in each app object

  |   Key    | Data Type |
  | :------: | :-------: |
  |  appId   |  Number   |
  | appName  |  String   |
  | imageUrl |  String   |
  | category |  String   |

</details>

<details>
<summary>Components Structure</summary>

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/app-store-component-structure-breakdown.png" alt="app store component structure breakdown" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

</details>


### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/app-store/app-store-search-img.png](https://assets.ccbp.in/frontend/react-js/app-store/app-store-search-img.png)

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #fff1eb; width: 150px; padding: 10px; color: black">Hex: #fff1eb</div>
<div style="background-color: #ace0f9; width: 150px; padding: 10px; color: black">Hex: #ace0f9</div>
<div style="background-color: #1e293b; width: 150px; padding: 10px; color: white">Hex: #1e293b</div>
<div style="background-color: #7b8794; width: 150px; padding: 10px; color: white">Hex: #7b8794</div>
<div style="background-color: #dfe2e5; width: 150px; padding: 10px; color: black">Hex: #dfe2e5</div>
<div style="background-color: #2563eb; width: 150px; padding: 10px; color: white">Hex: #2563eb</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>

</details>

<details>
<summary>Font-families</summary>

- Bree Serif

</details>

