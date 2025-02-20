# TMS
TMS/
├── backend/
│   ├── config/
│   │   ├── db.js
│   │   ├── appConfig.js
│   │   └── index.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── rideController.js
│   │   ├── userController.js
│   │   └── paymentController.js
│   ├── middlewares/
│   │   ├── authMiddleware.js
│   │   ├── errorHandler.js
│   │   └── requestLogger.js
│   ├── models/
│   │   ├── Ride.js
│   │   ├── User.js
│   │   ├── Payment.js
│   │   └── index.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── rideRoutes.js
│   │   ├── userRoutes.js
│   │   └── paymentRoutes.js
│   ├── services/
│   │   ├── paymentService.js
│   │   ├── rideService.js
│   │   ├── userService.js
│   │   └── notificationService.js
│   ├── utils/
│   │   ├── logger.js
│   │   ├── validator.js
│   │   ├── constants.js
│   │   └── helpers.js
│   ├── tests/
│   │   ├── controllers/
│   │   ├── services/
│   │   └── middlewares/
│   ├── .env
│   ├── app.js
│   ├── server.js
│   └── package.json
└── frontend/
    ├── android/
    │   ├── app/
    │   ├── build.gradle
    │   └── settings.gradle
    ├── ios/
    │   ├── TMS/
    │   ├── TMS.xcodeproj
    │   └── Podfile
    ├── src/
    │   ├── assets/
    │   │   ├── fonts/
    │   │   └── images/
    │   ├── components/
    │   │   ├── Button.js
    │   │   ├── Header.js
    │   │   └── MapView.js
    │   ├── navigation/
    │   │   ├── AppNavigator.js
    │   │   └── AuthNavigator.js
    │   ├── redux/
    │   │   ├── actions/
    │   │   │   ├── authActions.js
    │   │   │   ├── rideActions.js
    │   │   │   └── userActions.js
    │   │   ├── reducers/
    │   │   │   ├── authReducer.js
    │   │   │   ├── rideReducer.js
    │   │   │   └── userReducer.js
    │   │   ├── store.js
    │   │   └── actionTypes.js
    │   ├── screens/
    │   │   ├── LoginScreen.js
    │   │   ├── SignupScreen.js
    │   │   ├── RideDetailsScreen.js
    │   │   ├── RideHistoryScreen.js
    │   │   └── ProfileScreen.js
    │   ├── services/
    │   │   ├── api.js
    │   │   ├── authService.js
    │   │   ├── rideService.js
    │   │   └── notificationService.js
    │   ├── utils/
    │   │   ├── constants.js
    │   │   ├── helpers.js
    │   │   └── validators.js
    │   ├── App.js
    │   ├── index.js
    │   └── .env
    ├── .babelrc
    ├── .eslintrc.js
    ├── metro.config.js
    ├── package.json
    └── README.md
