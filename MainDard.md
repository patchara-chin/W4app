# W4app
Homework to design app

import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      title: 'ListViews',
      theme: ThemeData(
        primarySwatch: Colors.black,
      ),
      home: Scaffold(
        appBar: AppBar(title: Text('Gaming Gear Shop')),
        body: BodyLayout(),
      ),
    );
  }
}


class BodyLayout extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return _myListView(context);
  }
}

Widget _myListView(BuildContext context) {
  int total = 0;
  return ListView(
    children: <Widget>[
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/Logitech G pro 3990.jpg'),
        ),
        title: Text('Mouse Logitech G Pro'),
        subtitle: Text('Price: \฿3990'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+3990;
          print('Logitech G pro Price \n Total price = $total Baht');
        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/Logitech Gaming mouse G502 3790-.jpg'),
        ),
        title: Text('Logitech Gaming Mouse G502'),
        subtitle: Text('Price: \฿3790'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+3790;
          print('Logitech Gaming Mouse G502 \n Total price = $total Baht');
        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/Logitech-G413-Carbon-Backlit-Mechanical-Keyboard 2190.jpg'),
        ),
        title: Text('Logitech G413 Carbon Backlit'),
        subtitle: Text('Price: \฿2190'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+2190;
          print('Logitech G413 Carbon Backlit \n Total price = $total Baht');
        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/Logitech G213 RGB prodigy 1290-.jpg'),
        ),
        title: Text('Logitech G213 RGB prodigy'),
        subtitle: Text('Price: \฿2190'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+2190;
          print('Logitech G213 RGB prodigy\n Total price = $total Baht');
        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/hx-family-mouse-pulsefire-dart-md 3760-.jpg'),
        ),
        title: Text('HyperX mouse Pulsefire dart'),
        subtitle: Text('Price: \฿3760'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+3790;
          print('HyperX mouse Pulsefire dart \n Total price = $total Baht');
        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/HyperX-Pulsefire-Surge-RGB-Gaming-Mouse 1690.jpg'),
        ),
        title: Text('HyperX mouse Pulsefire Surge'),
        subtitle: Text('Price: \฿1690'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+1690;
          print('HyperX mouse Pulsefire Surge \n Total price = $total Baht');
        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/hx-product-keyboard-alloy-fps-rgb 3287-.jpg'),
        ),
        title: Text('HyperX keyboard Alloy FPS'),
        subtitle: Text('Price: \฿3287'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+3287;
          print('HyperX keyboard Alloy FPS \n Total price = $total Baht');
        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/hx-product-keyboard-alloy-origins-core 2890-.jpg'),
        ),
        title: Text('HyperX keyboard Alloy Origins'),
        subtitle: Text('Price: \฿2890'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+2890;
          print('HyperX keyboard Alloy Origins \n Total price = $total Baht');
        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/Razor Black widow 2019.jpg'),
        ),
        title: Text('Razor Black widow 2019'),
        subtitle: Text('Price: \฿3780'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+3780;
          print('Razor Black widow 2019 \n Total price = $total Baht');

        },
      ),
      ListTile(
        leading: CircleAvatar(
          backgroundImage: AssetImage('assets/images/Razor black widow Chroma V2 3990-.jpg'),
        ),
        title: Text('Razor black widow Chroma V2'),
        subtitle: Text('Price: \฿3990'),
        trailing: Icon(Icons.keyboard_arrow_right),
        onTap: () {
          total = total+3990;
          print('Razor black widow Chroma V2 \n Total price = $total Baht');
        },
      ),
    ],
  );
}

