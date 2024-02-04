# fictional-character


2
1
class FictionalCharacter {
2
  String name;
3
  int age;
4
​
5
  FictionalCharacter(this.name, this.age);
6
​
7
  void introduce() {
8
    print('Hello, I am $name, and I am $age years old.');
9
  }
10
}
11
​
12
void main() {
13
  FictionalCharacter merlin = FictionalCharacter('merlin', 27);
14
  merlin.introduce();
15
}
Console
Hello, I am merlin, and I am 27 years old.
