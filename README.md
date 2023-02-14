# share-and-url
share and url app
// share 2.0.4
import 'package:flutter/material.dart';
import 'package:share/share.dart';
import 'package:url_launcher/url_launcher.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      title: 'Flutter Demo',
      home: const MyHomePage(),
    );
  }
}

class MyHomePage extends StatefulWidget {
  const MyHomePage({super.key});

  @override
  State<MyHomePage> createState() => _MyHomePageState();
}

class _MyHomePageState extends State<MyHomePage> {
  final Uri _url = Uri.parse('https://www.youtube.com/watch?v=hvPbIo09OTE');
  Future<void> _launchUrl() async {
    if (!await launchUrl(_url)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url1 = Uri.parse('https://www.youtube.com/watch?v=OmD_ykd6azw');
  Future<void> _launchUrl1() async {
    if (!await launchUrl(_url1)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url2 = Uri.parse('https://www.youtube.com/watch?v=FPcl1tu0gDs');
  Future<void> _launchUrl2() async {
    if (!await launchUrl(_url2)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url3 = Uri.parse('https://www.youtube.com/watch?v=hz1xxKz9Gk8');
  Future<void> _launchUrl3() async {
    if (!await launchUrl(_url3)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url4 = Uri.parse('https://www.youtube.com/watch?v=uwSY9XqQGXw');
  Future<void> _launchUrl4() async {
    if (!await launchUrl(_url4)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url5 = Uri.parse('https://www.youtube.com/watch?v=_w4H5_Id9q8');
  Future<void> _launchUrl5() async {
    if (!await launchUrl(_url5)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url6 = Uri.parse('https://www.youtube.com/watch?v=rBVvJFh1NeE');
  Future<void> _launchUrl6() async {
    if (!await launchUrl(_url6)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url7 = Uri.parse('https://www.youtube.com/watch?v=EtG6QimIv_M');
  Future<void> _launchUrl7() async {
    if (!await launchUrl(_url7)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url8 = Uri.parse('https://www.youtube.com/watch?v=gEr9ahLeacY');
  Future<void> _launchUrl8() async {
    if (!await launchUrl(_url8)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url9 = Uri.parse('https://www.youtube.com/watch?v=I3Nfhna6JDY');
  Future<void> _launchUr9() async {
    if (!await launchUrl(_url9)) {
      throw Exception('Could not launch $_url');
    }
  }

  final Uri _url10 = Uri.parse('https://www.youtube.com/watch?v=SLD9xzJ4oeU');
  Future<void> _launchUrl10() async {
    if (!await launchUrl(_url10)) {
      throw Exception('Could not launch $_url');
    }
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
        appBar: AppBar(
          backgroundColor: Colors.white,
          elevation: 0.0,
          title: Text("Share Example", style: TextStyle(color: Colors.black)),
          iconTheme: IconThemeData(color: Colors.green),
          actions: [
            IconButton(
                onPressed: () {
                  Share.share(
                      "https://www.youtube.com/watch?v=q5DflHdUxas&t=202s");
                },
                icon: Icon(Icons.share))
          ],
        ),
        body: SafeArea(
          child: Padding(
            padding: const EdgeInsets.all(8.0),
            child: ListView(
              children: [
                InkWell(
                  onTap: _launchUrl,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse2.mm.bing.net/th?id=OIP.jWAiBJ7vKT3J7822S66PcgHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl1,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.MbUdPbaj4lmO8iW66Evg9wHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl2,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse4.mm.bing.net/th?id=OIP.fNy1KjxHYbwfIDKNX462vwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl3,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.k_-l0ORorg5k6SAvGRc0vwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl4,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse4.mm.bing.net/th?id=OIP.q4wyn1pCKQ-n1eVhMgUw7gHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl5,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.KAl9oL1TVYy8ngHdPvJWOAHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl6,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.s2o54mwXCalOA_kg44dWIwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl7,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.Cy3SDA8DIrTKJ_49S8mD_wHaDt&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl8,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse3.mm.bing.net/th?id=OIP.h1dtas4dyBu4Kbu3qyKRcgHaDt&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl10,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse3.mm.bing.net/th?id=OIP.s514mFjaaDLyOAenukdFoAHaEH&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl1,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse2.mm.bing.net/th?id=OIP.EBUnNBfjCr0TMG69M5bjsgHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse2.mm.bing.net/th?id=OIP.jWAiBJ7vKT3J7822S66PcgHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl1,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.MbUdPbaj4lmO8iW66Evg9wHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl2,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse4.mm.bing.net/th?id=OIP.fNy1KjxHYbwfIDKNX462vwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl3,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.k_-l0ORorg5k6SAvGRc0vwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl4,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse4.mm.bing.net/th?id=OIP.q4wyn1pCKQ-n1eVhMgUw7gHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl5,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.KAl9oL1TVYy8ngHdPvJWOAHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl6,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.s2o54mwXCalOA_kg44dWIwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl7,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.Cy3SDA8DIrTKJ_49S8mD_wHaDt&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl8,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse3.mm.bing.net/th?id=OIP.h1dtas4dyBu4Kbu3qyKRcgHaDt&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl10,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse3.mm.bing.net/th?id=OIP.s514mFjaaDLyOAenukdFoAHaEH&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl1,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse2.mm.bing.net/th?id=OIP.EBUnNBfjCr0TMG69M5bjsgHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse2.mm.bing.net/th?id=OIP.jWAiBJ7vKT3J7822S66PcgHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl1,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.MbUdPbaj4lmO8iW66Evg9wHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl2,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse4.mm.bing.net/th?id=OIP.fNy1KjxHYbwfIDKNX462vwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl3,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.k_-l0ORorg5k6SAvGRc0vwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl4,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse4.mm.bing.net/th?id=OIP.q4wyn1pCKQ-n1eVhMgUw7gHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl5,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.KAl9oL1TVYy8ngHdPvJWOAHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl6,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.s2o54mwXCalOA_kg44dWIwHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl7,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse1.mm.bing.net/th?id=OIP.Cy3SDA8DIrTKJ_49S8mD_wHaDt&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl8,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse3.mm.bing.net/th?id=OIP.h1dtas4dyBu4Kbu3qyKRcgHaDt&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl10,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse3.mm.bing.net/th?id=OIP.s514mFjaaDLyOAenukdFoAHaEH&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
                InkWell(
                  onTap: _launchUrl1,
                  child: Container(
                    height: 200,
                    width: 390,
                    child: Stack(
                      children: [
                        Image.network(
                          "https://tse2.mm.bing.net/th?id=OIP.EBUnNBfjCr0TMG69M5bjsgHaEK&pid=Api&P=0",
                          fit: BoxFit.cover,
                        ),
                        Padding(
                          padding: EdgeInsets.only(
                            top: 70,
                            left: 130,
                          ),
                          child: Icon(
                            Icons.play_circle_outline,
                            size: 50,
                            color: Colors.pink,
                          ),
                        )
                      ],
                    ),
                  ),
                ),
              ],
            ),
          ),
        ));
  }
}
