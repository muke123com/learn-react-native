#### react-navigation
```js
  //TabNavigator与StackNavigator嵌套使用
  const MainScreenNavigator = TabNavigator({
    Product: { screen: Product },
    Video: { screen: Video },
    Material: { screen: Material },
  },{
    tabBarPosition: 'bottom',
    tabBarOptions: {
      activeTintColor: '#ec6200',
      inactiveTintColor: '#333',
      style: {
        backgroundColor: '#fff',
      },
    },
  });

  const reactP1 = StackNavigator({
    Main: { screen: MainScreenNavigator },
    ProductDetail: { screen: ProductDetail },
  })

```
