import 'package:flutter/material.dart';

void main(){
  runApp(MaterialApp(
   home: HomePage(),
  ),
  );
}
class HomePage extends StatelessWidget{
  @override
  Widget build(BuildContext context) {

    return Scaffold( appBar: AppBar(
      title: Text("My App"),

    ) ,

        body:Center(child: Text('hello world',style: TextStyle(
          fontSize: 30,
           fontWeight: FontWeight.bold,
        ),
        )
        ),
      floatingActionButton: FloatingActionButton(onPressed: (){},
      child: Icon(Icons.add) ),
      drawer: Drawer(
        child: ListView(
           padding: EdgeInsets.all(0),
            children: [
          UserAccountsDrawerHeader(
            accountEmail: Text("Mahbubbengali@gmail.com"),
            accountName: Text('Kazi Mahbubur Rahman'),
            currentAccountPicture:  CircleAvatar(

              child: Text("K"),
            ),
          ),
              ListTile(
                onTap: (){},
                  leading: CircleAvatar(
                     child: Image.network("https://scontent.fcla1-1.fna.fbcdn.net/v/t1.0-9/120193356_816956395785800_9205050955884110663_n.jpg?_nc_cat=110&_nc_sid=174925&_nc_ohc=JtSP4roQyLEAX877gpl&_nc_ht=scontent.fcla1-1.fna&oh=02b0506b353d4550f8e824cb02e3d4a8&oe=5FA50620")
              ),
             // title: Text('Kazi Mahbubur Rahman'),
                subtitle: Text("Mahbub.Dev"),
                trailing: Icon(Icons.delete),

              ),
        ],

        ),
      ),
    );
  }

}
 









