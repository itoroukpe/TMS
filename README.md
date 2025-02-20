# TMS
```
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
   ```
    ---

    
    
    TMS/
├── backend/
│   ├── config/
│   │   ├── db.js
│   │   └── env/
│   │       ├── development.js
│   │       ├── production.js
│   │       └── test.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── driverController.js
│   │   ├── paymentController.js
│   │   ├── rideController.js
│   │   └── userController.js
│   ├── middlewares/
│   │   ├── authMiddleware.js
│   │   ├── errorHandler.js
│   │   └── requestLogger.js
│   ├── models/
│   │   ├── Country.js
│   │   ├── Driver.js
│   │   ├── Payment.js
│   │   ├── Ride.js
│   │   ├── User.js
│   │   └── index.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── driverRoutes.js
│   │   ├── paymentRoutes.js
│   │   ├── rideRoutes.js
│   │   ├── userRoutes.js
│   │   └── index.js
│   ├── services/
│   │   ├── blockchainService.js
│   │   ├── fraudDetectionService.js
│   │   ├── notificationService.js
│   │   ├── paymentService.js
│   │   ├── routeOptimizationService.js
│   │   └── userService.js
│   ├── utils/
│   │   ├── currencyConverter.js
│   │   ├── logger.js
│   │   ├── tokenGenerator.js
│   │   └── validator.js
│   ├── tests/
│   │   ├── controllers/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   ├── .env
│   ├── app.js
│   ├── package.json
│   └── README.md
└── frontend/
    ├── android/
    ├── ios/
    ├── src/
    │   ├── __tests__/
    │   │   ├── components/
    │   │   ├── screens/
    │   │   └── services/
    │   ├── assets/
    │   │   ├── fonts/
    │   │   └── images/
    │   ├── components/
    │   │   ├── Button.js
    │   │   ├── Header.js
    │   │   ├── RideCard.js
    │   │   └── index.js
    │   ├── hooks/
    │   │   └── useAuth.js
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
    │   │   │   ├── index.js
    │   │   │   ├── rideReducer.js
    │   │   │   └── userReducer.js
    │   │   ├── store.js
    │   │   └── types.js
    │   ├── screens/
    │   │   ├── Auth/
    │   │   │   ├── LoginScreen.js
    │   │   │   ├── OTPScreen.js
    │   │   │   └── SignupScreen.js
    │   │   ├── Driver/
    │   │   │   ├── DriverDashboard.js
    │   │   │   ├── EarningsScreen.js
    │   │   │   └── RideRequestsScreen.js
    │   │   ├── User/
    │   │   │   ├── HomeScreen.js
    │   │   │   ├── PaymentScreen.js
    │   │   │   ├── RideHistoryScreen.js
    │   │   │   └── RideRequestScreen.js
    │   │   └── index.js
    │   ├── services/
    │   │   ├── api.js
    │   │   ├── authService.js
    │   │   ├── notificationService.js
    │   │   └── paymentService.js
    │   ├── utils/
    │   │   ├── constants.js
    │   │   ├── helpers.js
    │   │   └── validators.js
    │   ├── App.js
    │   ├── index.js
    │   └── react-native.config.js
    ├── .babelrc
    ├── .eslintrc.js
    ├── metro.config.js
    ├── package.json
    └── README.md

