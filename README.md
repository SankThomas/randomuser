## What does the application do?

- It fetches random users from the random user API at [https://randomuser.me/api] and then displays their data including:

  1. Full name, i.e, name: {title, first, last}
  2. Gender
  3. Street Address
  4. Contact Details
  5. Geolocation i.e location: {latitude, longitude}

- You can clone the repository to see how the data we get back is destructured, or you can watch the YouTube video I will link below when I finish recording.

## What do we use?

1. `npx create-react-app` to canvas our React Application
2. TailwindCSS for our styling. I will be using the CDN as opposed to installing Tailwind.
3. Roboto Slab font from [Google Fonts](https://fonts.google.com) - which I have not used in this project but will update later.
4. Moment.js which is a library for formating JavaScript dates. Install moment by using `npm install moment --save`

- It is important to note that Moment.js documentation recommend that you use another library to format dates because they are in maintenance mode, but since this is a small project, it's okay to use Moment.js

5. `npm install react-icons --save` which will be our icon library.
6. The most important of course is the actual API, which comes from [randomuser.me/api](https://randomuser.me/api). You can find the link in the `.txt` file as well in the workspace.

### Video benefits

1. I will show multiple ways to display our data, including destructuring the JSON data we get back from the `fetch API`
2. I will showcase 2 ways of using the `useEffect` hook in react, i.e fetching data from within and outside the hook.
3. I'm thinking of installing `axios` to handle our data fetching because it's more secure than the `fetch API` and it also poses a more challenging experience, and you can learn multiple ways of fetching data.

#### WhoAmI?

I am Thomas Sankara
