# cod_2
import 'package:flutter/material.dart';

class Myapp extends StatelessWidget {
  const Myapp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Container(
      decoration: const BoxDecoration(
          color: Colors.blue,
          borderRadius: BorderRadius.all(
            Radius.circular(10.0),
          )),
      height: 200,
      width: 350,
      child: Column(children: [
        Row(children: [
          Container(
              decoration: const BoxDecoration(
                  color: Colors.blue,
                  borderRadius: BorderRadius.all(
                    Radius.circular(10.0),
                  )),
              height: 70,
              width: 100,
              child: Image.network(
                  'https://cdn-icons-png.flaticon.com/512/25/25634.png')),
          Column(children: [
            Divider(),
            Row(
              mainAxisAlignment: MainAxisAlignment.spaceBetween,
              children: const [
                const Text(
                  'Name:',
                  style: TextStyle(
                    color: Colors.white,
                    fontSize: 15.0,
                  ),
                )
              ],
            ),
            Row(
              mainAxisAlignment: MainAxisAlignment.spaceBetween,
              children: const [
                const Text(
                  'Phone:',
                  style: TextStyle(
                    color: Colors.white,
                    fontSize: 15.0,
                  ),
                )
              ],
            ),
            Row(
              mainAxisAlignment: MainAxisAlignment.spaceBetween,
              children: const [
                const Text(
                  'Gmail:',
                  style: TextStyle(
                    color: Colors.white,
                    fontSize: 15.0,
                  ),
                )
              ],
            ),
            const SizedBox(height: 80),
            Column(children: [
              Row(mainAxisAlignment: MainAxisAlignment.spaceEvenly, children: [
                Container(
                    height: 20,
                    width: 50,
                    decoration: BoxDecoration(
                      borderRadius: BorderRadius.circular(10),
                      color: Colors.white,
                    ),
                    child: Image.network(
                        'https://w7.pngwing.com/pngs/991/629/png-transparent-litter-rubbish-bins-waste-paper-baskets-sign-symbol-symbol-miscellaneous-text-recycling.png')),
                Container(
                    height: 20,
                    width: 50,
                    decoration: BoxDecoration(
                      borderRadius: BorderRadius.circular(10),
                      color: Colors.white,
                    ),
                    child: Image.network(
                        'https://e7.pngegg.com/pngimages/241/54/png-clipart-heart-symbol-heart-love-text.png')),
                Container(
                    height: 20,
                    width: 50,
                    decoration: BoxDecoration(
                      borderRadius: BorderRadius.circular(10),
                      color: Colors.white,
                    ),
                    child: Image.network(
                        'https://w7.pngwing.com/pngs/607/290/png-transparent-computer-icons-symbol-sign-share-icon-symbol-miscellaneous-cdr-angle.png')),
              ])
            ])
          ])
        ])
      ]),
    );
  }
}
