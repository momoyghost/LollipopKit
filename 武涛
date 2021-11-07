import 'dart:io';

enum Emotion {
  happy,
  sad,
  angry,
  }
  class Person {
  String name;
  int age;
  Emotion emo;
  Person(this.name, this.age, this.emo);
  void printlnfo() {
  print("name：${this.name}\n,age:${this.age}\n,emo：${this.emo}");
  }

   String toString() {
    return 'Persion<$name,$age,$emo>';
   }
  }
  void testCustomClass() {
    print(Person);
    Person person = Person("Jack", 21, Emotion.happy);
    person.printlnfo();
  }
main() {
  final p = Person('Jack', 21, Emotion.happy);
  print(p);
}
  void getSchedule() async {
    final file = File('Person.json');
    final content = await file.readAsString();
    print(content);
   }
