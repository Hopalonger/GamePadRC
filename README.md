# GamePadRC
A simple Set of Code to Control a RC device with a xbox 360 

#Setup 
## isntall Python Librarys
 ```python
  pip install inputs
  pip install colorama
```
```shell
python Setupnrf24.py install
```


**Problem statement:**

Almost everyone has played video games of some sort, many people play games every day. Many of these games or gaming systems have there owned ergonomic way to interact with the game. However when performing similar tasks using remote control vehicles the way to interact with the vehicle gets brought back to 1985 levels, where the controllers are bulky, unergonomic, and counterintuitive. When just using an RC transmitter many people find that it is lacking the overall form that is needed for it to be easy to use. This lack of ease of use not only increases the learning curve of using RC craft. With this very steep learning curve it can result in out of control crafts that are both unsafe but also can be very costly as many crafts are quite expensive.

To see the problem, I ask friends who play video games with controllers to fly an RC plane with a Generic RC transmitter, many of them struggled to get it to take off and keep it in the sky. The end result for all of them was a crash or failed landing. This disconnect is between the user and the brain even with gaming experience.

**Existing Designs:**

![](cid:Image_0.jpg)

**https://static.rcgroups.net/forums/attachments/2/2/5/6/4/a12019143-123-13.jpg**

![](cid:Image_1.png)

**https://cinegears.com/wp-content/uploads/2016/08/3-083\_FUTUBA-Yota\_Gimbal\_Car\_Remote\_Control.png**

![](cid:Image_2.png)

https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwiasfCtwbDmAhU9JTQIHQ-2DwMQjRx6BAgBEAQ&url=https%3A%2F%2Faeromodellingtutor.in%2Fproducts%2Fflysky-new-rc-plane-remote-controller-fs-i6x-latest-i-bus-6-channel-receiver&psig=AOvVaw0eUbjIAcHkN9HrIR8jHA6J&ust=1576253859633307

**Design Brief:**

I have identified a problem when using RC controllers there is a high learning curve which results in the destruction of the craft and injury to people around the craft. With this problem identified I will create a solution that benefits the user flying the craft. These benefits would include better ergonomics, a lower learning curve, and higher overall safety.

From my research, I extrapolated that many people are interested in RC and have experience using gaming interface devices. I am focusing on a specific segment for the design i.e. the RC hobbyist/electronics enthusiast market where they could modify their craft and create their own rendition.

The product must be:

*   Be usable for customers

*   Robust and reliable
*   Portable
*   Easy to build
*   Cheap to manufacture

The product that I would make would be a Wireless interface between a USB gaming input and an RC craft.

**Design Specification**

**Target Market:** the RC controller market with millennials and younger in mind, but there is the ability for the aesthetics and user interface to be updated to target different ages and skills.

**Target Audience:** This product is targeted towards people entering or already members of the RC hobbies. The product has no specific gender but there is the gaming skill required which results in an Age range of about 10 - 40 years old. Based on quick searches for RC crafts we see that prices tend to be in the $200+, and if we search for RC controllers we see a minimum price of $40. This indicates that our target Audience is willing to spend money on the product.

**User Need:** It must be able to be brought out into the environment and withstand semi harsh conditions without breaking. It also must be intuitive to use and easy to see if it is working. The product must be safe and have easy ways to see if the system is working. It also must be able to be easily transported.

**Competition:** This product must stand out but also have the overall feel that is similar to other RC controllers. The receiver must also be compatible with the interfacing standards. I will also be looking at other products to see what is needed in the interface such as features that are common with the RC transmitters and receivers.

**Size:** This product must be small enough to be carried in a bag or a large pocket. The device also must be useful outside of the home which requires it to be able to get power from common portable power sources or have a power source that is built in.

**Safety:** This device must not distract the user unintentional ways, this forces the design to have no edges that could scratch the user and distract the user. There also must be an interface so the user can easily get the state of the device without being distracted from operating there RC craft. This device also must not damage any of the devices that are interfacing with it.

**Materials:** Must be robust and lightweight. Must allow for some heat to be dissipated in the environment so electronics can safely operate. These materials must also not cause environmental damage when used.

**Aesthetics:** This device must be able to interface with the game controllers but still have the feel and robust look of RC hardware. The color of the case should be noticeable if it were to be lost in an outdoor environment but not distracting of the user.

**Cost:** This device needs to be relatively low cost. When analyzing competing products we see that the closest similar product costs $200. With this price in mind a good target price would be that or lower. This price would also need to include a game controller such as the Xbox One Controller which costs $50. This would leave us with a max price of $150. This would work with the market based off the prices of RC crafts, but when we search for RC plane controllers (they have the most interfacing channels) we see that the first results are in the $80 price range. This would be a better target price for the Device as it would replace the controller. This $80 does not include the controller because the Target Audience should have some gaming experience and a gaming controller to go with this experience.

**Environment:** This device should be built with as many recycled materials as possible, such as recycled plastics for the case. Also having user replaceable parts and easy access to the internal components so that the user can replace or upgrade certain parts instead of buying a completely new device.

**Performance requirements:** This device must be able to hold the components that convert the signals given from common game controllers into radio frequencies that are decoded into PWM signals that can be interpreted by RC Crafts while in most environments.This requires high precision and reliability. This also requires that this converter is not only completely safe when the user interacts with it but it also must be able to withstand the environment, which includes moisture, impacts, high heat, extreme cold and constant vibrations. The receiver of the system must be low enough power to run off of the power supplied by the RC crafts.
