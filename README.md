# ✨ Flutter Animation Set

[![pub package](https://img.shields.io/pub/v/flutter_animation_set.svg)](https://pub.dev/packages/flutter_animation_set)

**[Lanuage ~~]** [English](README.md) | [中文文档](README_CN.md)

Simplified Flutter stagger animation.To drive the Flutter stagger animation through a timeline in the form of an animation configuration.You can

1. Uses the existing Animation Widget of `Flutter Animation Set`
2. Use `Flutter Animation Set` to create a new Animation Widget
3. Contribute your Flutter Animation Set Widget
4. Watch All of the `Curves` of Flutter in example

## 🎖 Installing

```yaml
dependencies:
  flutter_animation_set: ^0.0.4
```

## ⚡ Use Animation Set Widget

**1、import**

```dart
import 'package:flutter_animation_set/widget/transition_animations.dart';
import 'package:flutter_animation_set/widget/behavior_animations.dart';
```

**2、use**

```dart
child: YYRotatingPlane(),
```

**3、road map**

> transition_animations

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/1.gif" width="90px">
      <br />
      YYRotatingPlane
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/2.gif" width="90px">
      <br />
      YYDoubleBounce
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/3.gif" width="90px">
      <br />
      YYWave
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/4.gif" width="90px">
      <br />
      YYWanderingCubes
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/5.gif" width="90px">
      <br />
      YYFadingFour
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/6.gif" width="90px">
      <br />
      YYFadingCube
      <br />
      ✅
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/7.gif" width="90px">
      <br />
      YYPulse
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/8.gif" width="90px">
      <br />
      YYThreeBounce
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/9.gif" width="90px">
      <br />
      YYThreeLine
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/10.gif" width="90px">
      <br />
      YYCubeGrid
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/11.gif" width="90px">
      <br />
      YYRotatingCircle
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/12.gif" width="90px">
      <br />
      YYPumpingHeart
      <br />
      ✅
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/13.gif" width="90px">
      <br />
      YYRipple
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/14.gif" width="90px">
      <br />
      YYRotateLine
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/15.gif" width="90px">
      <br />
      YYCubeFadeIn
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/16.gif" width="90px">
      <br />
      YYBlinkGrid
      <br />
      ✅
    </td>
  </tr>
</table>

> behavior_animations

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/17.gif" width="90px">
      <br />
      YYFadeButton
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/18.gif" width="90px">
      <br />
      YYSingleLike
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/19.gif" width="90px">
      <br />
      YYLove
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/20.gif" width="90px">
      <br />
      YYSpringMenu
      <br />
      ✅
    </td>
    <td align="center">
      <img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/21.gif" width="90px">
      <br />
      YYFoldMenu
      <br />
      ✅
    </td>
  </tr>
</table>

**4、thanks**

* [flutter_spinkit](https://github.com/jogboms/flutter_spinkit)

## ⚡ Create Animation Set Widget By YourSelf

**1、import**

```dart
import 'package:flutter_animation_set/animation_set.dart';
import 'package:flutter_animation_set/animator.dart';
```

**2、use widget**

```dart
AnimatorSet(
    child: widget.child,
    animatorSet: [],
    animationType: AnimationType.reverse,
    debug: false,
)
```

AnimatorSet Supported properties

Property|Mean|Default
:--|:--|:--:|
child|The component that performs the animation|not have
animatorSet|Collection of animation|not have
animationType|Controls the type of animation execution|AnimationType.repeat
debug|The output log|false

The properties of the animationType

Property|Mean
:--|:--|
repeat|Repeat animation
reverse|Rewind animation
once|One play animation

**3、use AnimatorSet api**

about animation widget

Widget|Mean|Description
:--|:--|:--:|
**W**|width|Control the change of width. If it is scaled up, SX is recommended instead
**H**|height|Control the change of height. If it is scaled up, SY is recommended instead
**P**|padding|Control padding changes
**O**|opacity|Control opacity changes
**SX**|scaleX|Scale the X-axis with the midpoint
**SY**|scaleY|Scale the Y-axis with the midpoint
**RX**|rotateX|Rotate the X-axis with the midpoint
**RY**|rotateY|Rotate the Y-axis with the midpoint
**RZ**|rotateZ|Rotate the Z-axis with the midpoint
**TX**|transitionX|Translate the Z-axis with the midpoint
**TY**|transitionY|Translate the Y-axis with the midpoint
**C**|color|Control background color changes
**B**|border|Control background border changes

about support widget

Widget|Mean|Description
:--|:--|:--:|
**Delay**|delay timeLine|Extend the timeline to wait
**Serial**|combine animation|Through the combination of animation, to achieve the effect of playing together

## ⚡ For Example

**1、create timeLine**

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/readme/YYWave.png" width="800px">
<br />

1. This figure shows that the core components of the animation are made according to the timeLine
2. In the process of execution, there are 6 animations simultaneously, and the total animation duration is 900ms
3. ScaleY components are used to scale up and down in order to make each rectangle have a wave effect
4. Drag the timeline with the Delay component to reach the animation duration of 900ms

**2、build animatorSet**

Assemble our animation component using the diagram above, which has the following properties

* from:Animation initial value
* to:End of animation value
* duration:Animation time
* delay:The delay in actually executing the animation
* curve:Animation interpolator

```dart
animatorSet: [
  Delay(duration: before),
  SY(from: 0.8, to: 1.6, duration: 200, delay: 0, curve: Curves.linear),
  SY(from: 1.6, to: 0.8, duration: 200, delay: 0, curve: Curves.linear),
  Delay(duration: after),
],
```

The object that the animation executes is `Container` rectangle

```dart
Widget makeWave(int before, int after) {
  return AnimatorSet(
    child: Container(
      color: Colors.white,
      width: 5,
      height: 15,
    ),
    animatorSet: [
      Delay(duration: before),
      SY(from: 0.8, to: 1.6, duration: 200, delay: 0, curve: Curves.linear),
      SY(from: 1.6, to: 0.8, duration: 200, delay: 0, curve: Curves.linear),
      Delay(duration: after),
    ],
  );
}
```

**3、convert to code**

```dart
class YYWave extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
      width: 40,
      height: 40,
      child: Row(
        mainAxisAlignment: MainAxisAlignment.spaceBetween,
        children: <Widget>[
          makeWave(0, 500),
          makeWave(100, 400),
          makeWave(200, 300),
          makeWave(300, 200),
          makeWave(400, 100),
          makeWave(500, 0),
        ],
      ),
    );
  }
}
```

**4、done**

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/3.gif" width="90px">

## More

**1、Combination of animation**

> The scaling effect requires scaling both the X and Y axes, uses the Serial Widget

```dart
animatorSet: [
  Serial(
    duration: 2000,
    serialList: [
      SX(from: 0.0, to: 1.0, curve: Curves.easeInOut),
      SY(from: 0.0, to: 1.0, curve: Curves.easeInOut),
      O(from: 0.5, to: 0.0, delay: 1000, curve: Curves.easeInOut),
    ],
  ),
],
```

done

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/7.gif" width="90px">

**2、Time-lapse animations**

Deal with the delay attribute when you actually do the animation

```dart
class YYThreeLine extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
      width: 40,
      height: 40,
      child: Row(
        mainAxisAlignment: MainAxisAlignment.spaceBetween,
        children: <Widget>[
          makeLine(0),
          makeLine(50),
          makeLine(100),
        ],
      ),
    );
  }
}

Widget makeLine(int delay) {
  return AnimatorSet(
    child: Container(
      color: Colors.white,
      width: 10,
      height: 5,
    ),
    animatorSet: [
      TY(from: 0.0, to: 5.0, duration: 400, delay: delay, curve: Curves.fastOutSlowIn,),
      TY(from: 5.0, to: 0.0, duration: 400, curve: Curves.fastOutSlowIn,),
    ],
  );
}
```

done

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/9.gif" width="90px">

**3、Reverse animation**

After the animation can be played, set `animationtype.reverse` through the animationType property, making the animation play back

```dart
class YYFoldMenu extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
      width: 40,
      height: 40,
      child: Column(
        mainAxisAlignment: MainAxisAlignment.spaceBetween,
        children: <Widget>[
          makeFoldMenu(0, 40),
          makeFoldMenu(100, 26.0),
          makeFoldMenu(200, 12.0),
        ],
      ),
    );
  }
}

Widget makeFoldMenu(int delay, double toY) {
  return AnimatorSet(
    animationType: AnimationType.reverse,
    child: Container(
      decoration: BoxDecoration(
        color: Colors.white,
      ),
      width: 30,
      height: 10,
    ),
    animatorSet: [
      Serial(
        duration: 2000,
        delay: delay,
        serialList: [
          TY(from: 0.0, to: toY, curve: Curves.elasticInOut),
          SX(from: 1.0, to: 0.1, curve: Curves.elasticInOut),
          SY(from: 1.0, to: 0.1, curve: Curves.elasticInOut),
        ],
      ),
    ],
  );
}
```

done

<img src="https://github.com/efoxTeam/flutter-animation-set/raw/master/image/gif/21.gif" width="90px">

## Bugs/Requests

* If your application has problems, please submit your code and effect to Issue.
* Pull request are also welcome.

## Contribution

* Contribute your component, and we'll add it to the animation set
* Or post your animation, if interested, we will help you to achieve

## About

* QQ：510402535
* QQ群：798874340
* e-mail：xyj510402535@qq.com
* g-mail：xyj51042535@gmail.com
* Blog：http://blog.csdn.net/qq_30379689
* Github：https://github.com/AndroidHensen

## License

Apache License 2.0
