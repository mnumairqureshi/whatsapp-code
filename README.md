# whatsapp-code





import 'package:flutter/material.dart';

void main() => runApp(myapp());

class myapp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold(
          appBar: AppBar(
            backgroundColor: Colors.orange,
            leading: const Icon(Icons.menu),
            title: Text("Hunger's Home Kitchen"),
            actions: [Text("PK")],),
          body: SingleChildScrollView(
            child: Column(
              children: [
                ListTile(
                  leading: CircleAvatar(
                    radius: 25,
                    backgroundColor: Colors.yellow,),
                  title: Text("Numair"),
                  subtitle: Text("hello"),
                  trailing: Column(children: [
                    Text("8:00pm"),
                    Text("8:55pm"),]),)],),)),);}}
