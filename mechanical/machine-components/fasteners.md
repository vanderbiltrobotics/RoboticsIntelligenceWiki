<!-- TITLE: Fasteners -->
<!-- SUBTITLE: A quick summary of Fasteners -->

# Overview
Fasteners are a very broad group of mechanical devices that joins or fixes two objects together. All of you have definitely used some sort of fastener like a screw, bolt, nail, but often times there are better options. The intent of this article is to give a survey of common fasteners used, as well as how to understand the sizing of them. Feel free to add any other type of fastener to this article.

# Types
## Bolts
![Rsz Home Mid 01](/uploads/machine-components/rsz-home-mid-01.jpg "Rsz Home Mid 01")
Bolts are the most common type of fastener we use on the robot, as they are simple and non-permanent. The typical bolts used on this team are socket head (as phillips head screw strip easier, among other reasons). To negate the effects of vibration loosening the bolt, locktite and/or locknuts are used. To learn about larger varieties of bolts, there are much better resources than this article, such as http://blog.mutualscrew.com/2015/07/07/different-types-of-bolts/.

When picking bolts, it is important to consider strength, size, and standardization. The first is honestly not much of a consideration, as it is very unlikely for you to design a system capable of shearing a bolt of any reasonable size, but do use common sense. Same thing for size, make sure your bolt can go through all of the parts it connects, and there is clearance for both the head and the nut. (Might seem like a dumb thing to mention, but there are many cases where someone has designed a system where they didn't take into account the bolts used until the end and had to redesign due to not havign the clearance necessary.)  Lastly, standardization is important not just for bolts, but all fasteners. Choosing 5 different sizes of fasteners for a subsystem with no particular reason adds unnecessary complexity. For this reason , we typically use 10-24 thread size bolts. 
### Thread Sizing
Thread size for bolts are defined in either imperial or metric (as is most things in engineering). For the imperial sizing, bolts are defined with "x-y", where x defines the bolt diameter (use a chart to find out this diameter in inches), and y defines the thread density (y threads per inch). For the metric system, the entire system is arbitrary, so google "metric thread size chart" to find what M4, M6, etc. mean. 
## Nails and Screws
Neither of these are used on the robot, so this is more of an explanation of why these two commonly used fasteners are bad for our application. Nails are bad because they are much better suited for woodworking. Screws are bad because they require that the hole be threaded to work, making bolts just better to use.
## Rivets
![Rsz 71 Lmu 3 Gtcgl Sx 425](/uploads/machine-components/rsz-71-lmu-3-gtcgl-sx-425.jpg "Rsz 71 Lmu 3 Gtcgl Sx 425")
Rivets are a permanent fastener, that have the upside of being easy to install, compact, and light (although they can also be removed with the use of a drill). The most common type of rivet is a blind rivet, which work by forcing a metal cylinder through another hollow one, deforming the rivet to secure the two parts together. For choosing the rivet, make sure to pick the correct length as you need at least 1/8" more than the thickness of the materials being bound. The shear and tensile strength specs are usually given, so use that to determine the material and diameter to use.
![Popnagel](/uploads/machine-components/popnagel.gif "Popnagel")
## Retaining Rings
![Rsz Download 1](/uploads/machine-components/rsz-download-1.jpg "Rsz Download 1")
Retaining rings are used to fasten or transfer load from components onto a shaft. They are expandable rings that you "snap" into a groove, where the portion outside of the groove prevents any part on the shaft from moving past it. Thus, they are frequently used to secure a gear or wheel on a shaft where an entire coupler is not necessary. For choosing a retaining ring type or material, I suggest https://www.machinedesign.com/archive/using-retaining-rings-properly.
## Clevis Pins
![Rsz 1 Wfd 4 As 01](/uploads/machine-components/rsz-1-wfd-4-as-01.jpg "Rsz 1 Wfd 4 As 01")
Clevis pins are often used to fasten parts that need to be quickly disassembled, where bolts and rivets are undesirable. It is simply a rod with a hole on the end to insert a split pin, securing the rod. Since the pin doesn't actually place any pressure between the two parts, clevis pins are not good at securing rotation or vibration. 
