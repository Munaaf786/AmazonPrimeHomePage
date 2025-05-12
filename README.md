# **Prime Video App**

In this project, I have built a **Prime Video App** by applying the concepts I have learned till now.

### Refer to the video below for Output:

<br/>
<div style="text-align: center;">
  <video style="max-width:80%; box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12); outline:none;" loop="true" autoplay="autoplay" controls="controls" muted>
    <source src="https://assets.ccbp.in/frontend/content/react-js/prime-video-output.mp4" type="video/mp4" />
  </video>
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/prime-video-lg-output-img.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`

</details>

### Completed Following Instructions

<details>
<summary>Functionality added</summary>
<br/>

The app has the following functionalities:

- **Action Movies List** and **Comedy Movies List** are displayed using **React Slick**
- The app is provided with a `moviesList` consisting of movie item objects with:
  - `id` (String)
  - `thumbnailUrl` (String)
  - `videoUrl` (String)
  - `categoryId` (String)
- Clicking the **next button** on the slider shows next set of movie thumbnails
- Clicking the **previous button** shows the previous set of thumbnails
- Clicking on a **thumbnail** opens a popup
  - The popup plays the corresponding video using **React Player**
  - Clicking the **close button** closes the popup

</details>

<details>
<summary>Components Structure</summary>

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/prime-video-compoment-structure-breakdown.png" alt="component structure breakdown" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

</details>

<details>
<summary>Implementation Files</summary>
<br/>

Used these files to complete the implementation:

- `src/components/PrimeVideo/index.js`
- `src/components/PrimeVideo/index.css`
- `src/components/MoviesSlider/index.js`
- `src/components/MovieItem/index.js`
- `src/components/MovieItem/index.css`

</details>

### Quick Tips

<details>
<summary>Click to view</summary>

- Use the following libraries as needed:
  - [React Slick](https://learning.ccbp.in/frontend-development/course?c_id=2f4192f7-7495-49ca-a6ce-6b74005e25f1&s_id=c1dc8b6e-864b-4417-9767-471b9e745405&t_id=416f0cab-8425-413b-9157-c7b4d4ae4467)
  - [React Popup](https://learning.ccbp.in/frontend-development/course?c_id=2f4192f7-7495-49ca-a6ce-6b74005e25f1&s_id=b01fca1c-aa5c-4d79-b81e-0220e7649bd0&t_id=416f0cab-8425-413b-9157-c7b4d4ae4467)
  - [React Player](https://learning.ccbp.in/frontend-development/course?c_id=2f4192f7-7495-49ca-a6ce-6b74005e25f1&s_id=b6392b63-25f6-4215-be09-9f23ad91d789&t_id=416f0cab-8425-413b-9157-c7b4d4ae4467)

- To style the popup content, use `.popup-content`:

```jsx
<Popup
  modal
  trigger={
    // write your code here
  }
  className="popup-content"
>
  // write your code here
</Popup>
```

</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

**The following instructions are required for the tests to pass**

- One frame of the slider should display 4 thumbnails
- All thumbnail images should have alt text as **thumbnail**
- The close button in the popup should have `data-testid="closeButton"`
- Use `IoMdClose` from `react-icons` for the popup close icon

</details>

### Resources Used

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/prime-video-img.png](https://assets.ccbp.in/frontend/react-js/prime-video-img.png) – alt: **prime video**

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #000000; width: 150px; padding: 10px; color: white">Hex: #000000</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #231f20; width: 150px; padding: 10px; color: white">Hex: #231f20</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>

### Conclusion

- 🎬 This project demonstrates the use of `React Slick`, `React Popup`, `React Player`, and dynamic rendering of video content.
- This app is **designed only for large devices** (laptops, desktops, or tablets). If you're trying to view it on a mobile device, please open it in **Desktop Mode** using your browser (e.g., Chrome mobile → three dots → "Desktop site").
- Thanks for checking out my **Prime Video App**! It showcases my skills in component-driven development, UI interaction, and third-party library integration using React.

- 🔗 Check it out here: [https://primevideo.ccbp.tech](https://amazonprime.ccbp.tech/)

Happy streaming! 🍿
