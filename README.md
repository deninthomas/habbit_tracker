# 🎯 Habit Hero

A beautiful and intuitive habit tracker to help you build better routines and stay consistent with your goals.

![Habit Hero](https://img.shields.io/badge/React-18.x-blue) ![CSS3](https://img.shields.io/badge/CSS3-Styled-green)

## ✨ Features

### Core Functionality
- **Create Habits**: Add new habits with customizable properties
  - Name your habit
  - Set frequency (daily or weekly)
  - Choose from 6 categories (Health, Work, Learning, Fitness, Mental Health, Productivity)
  - Set a start date
  
- **Track Progress**: Stay on top of your habits
  - Quick check-in with a single click
  - Add notes to track your thoughts and progress
  - Visual feedback for completed habits
  
- **View Analytics**: Understand your patterns
  - Current streak tracking
  - Success rate calculation
  - Total check-ins count
  - Best day analysis (which day of the week you're most consistent)
  
- **Multiple Views**:
  - **Dashboard**: Overview of all habits with quick stats
  - **Calendar**: Weekly view to track habits across 7 days
  - **Analytics**: Detailed statistics for each habit
  - **Details**: In-depth view with notes and full statistics

### Additional Features
- **Data Persistence**: All data saved to localStorage
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Beautiful UI**: Modern gradient design with smooth animations
- **Category Icons**: Visual representation with emojis
- **Empty States**: Helpful messages when no data exists

## 🚀 Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## 🛠️ Tech Stack

- **Frontend**: React 18.x (JSX)
- **Styling**: Pure CSS3 with modern features
  - CSS Grid & Flexbox
  - Gradient backgrounds
  - Smooth animations and transitions
  - Responsive media queries
- **State Management**: React Hooks (useState, useEffect)
- **Data Storage**: Browser localStorage
- **Build Tool**: Create React App

## 📱 How to Use

1. **Add a Habit**: Click the "+ Add Habit" button on the dashboard
2. **Fill in Details**: Enter habit name, frequency, category, and start date
3. **Track Daily**: Click the check button to mark a habit as complete for the day
4. **View Calendar**: Switch to calendar view to see your weekly progress
5. **Check Analytics**: View detailed statistics for each habit
6. **Add Notes**: Click "View Details" on any habit to add notes and see full stats
7. **Delete Habits**: Use the delete button in the details view to remove habits

## 🎨 Design Features

- **Color Scheme**: Purple gradient theme (#667eea to #764ba2)
- **Typography**: System fonts for optimal performance
- **Icons**: Emoji-based category icons
- **Animations**: Smooth hover effects and transitions
- **Cards**: Rounded corners with subtle shadows
- **Responsive**: Mobile-first design approach

## 📊 Analytics Explained

- **Streak**: Consecutive days you've completed the habit
- **Success Rate**: Percentage of days completed since start date
- **Best Day**: Day of the week with most check-ins
- **Total Check-ins**: Overall number of times you've completed the habit

## 🔒 Privacy

All your habit data is stored locally in your browser's localStorage. No data is sent to any server, ensuring complete privacy.

## 📝 License

This project is open source and available under the MIT License.
