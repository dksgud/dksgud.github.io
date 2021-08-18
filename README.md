

import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: '아이를 위한 AI',
      home: Grade(),

      
    );
  }
}

class Grade extends StatelessWidget {
  

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: Colors.amber[800],
      appBar: AppBar(
        title: Text('아이를 위한 AI'),
        backgroundColor: Colors.amber[700],
        centerTitle: true,
        elevation: 0.0,
      ),
      body: Padding(
        padding: EdgeInsets.fromLTRB(30.0, 40.0, 0.0, 0.0),
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            Container(
              child: Image(
                image: AssetImage('assets/turtle.png'),
                width: 200,
                
              ),
              
            
            ),
             Container(
              child: Image(
                image: AssetImage('assets/eye.png'),
                width: 200,
                
              ),
              
            
            ),
              
             
            

            
            
               
              ],
            )
          
        ),

        
      
      
    );
  }
}

