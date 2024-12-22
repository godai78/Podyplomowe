# 4-color process in Adobe Photoshop — creating the retro comic color halftones the easy and free way

My generation (and the older folks as well) probably remember the comic books of our teenage years, the Polish reprints of Marvel and DC brought in the 90s by TM-Semic. One of the iconic elements of those comics was a terribly poor print on cheap paper and the 4CP method, i.e. four-color process. Tiny dots of color were printed one over the other to create a mixture that could produce any color. These dots were red, blue, and yellow (well, almost that!) and black on top (sometimes on the bottom, things were hasty). Up till this day printing four basic colors (cyan, magenta, yellow and black) in layers is one of the basic methods of color printing.
A panel from “Detective Comics” #31.

This panel from Detective Comics #31 clearly shows the famous dots. © DC Comics

We later learned these dots are called halftones and the process of splitting colors into layers is called separation. The 90s came with the terrible computer coloring, then the 21st century made everything decent again, and now color halftones are more of a part of vaporwave nostalgia than anything else, as modern comics print quality is something completely different…

What is the point of simulating it now? Nostalgic, as mentioned. Artistic. Freedom of expression, impressing the viewer, striking a chord. These are the aims of the tutorial that follows, but not only. It can be used as a starting process for screen printing, stamping (well, that would be very detailed and difficult probably, laser cutting would be a must), or whatever. What I know is that people pay heavy bucks for textures and brushes when they could achieve a much more real effect for free.

The following description and pictures were done in Photoshop CS2, but there have not been as many changes to the interface since then and everything should be clearly understandable.

The picture used to illustrate the process is my own recreation of a comic panel by Marc Silvestri, from the Wolverine solo series from 1990.

    Load the image and make sure the resolution is 300DPI. This is the industry standard for color printing, both offset and digital. You may settle for less if you aim at online publication and screen only. This will produce larger halftones and you will need to adjust this value during step 4.

2. Change the color mode to CMYK. That’s a popular printing solution.

3. Duplicate the file four times, naming the new files respectively C, M, Y, and K. They will become the bases for separate color halftones, respectively cyan, magenta, yellow and black (the relation seems apparent).

4. Now’s the difficult moment. Enter the channels palette on file C, choose Cyan, and convert the channel into a bitmap (disregard other channels).

Choose the right resolution — 300DPI is the default unless you decided to employ a different one in step 1. This affects halftone dots sizes in the effecting file.

Set the frequency to 60 lines, and choose the round shape. We will deal with the angle in a moment.

The frequency affects the density and size of the dots, so if you want the large and visible like Roy Liechtenstein’s (the guy that stole other artists drawing and earned millions when they got nothing) you have to toy with that until you are satisfied with the results. 60 produces a nice, dense effect, perfect for printing on paper.

As for the angle (and this is very important!), the values should be set as follows:

    for cyan 15°
    black 45°
    magenta 75°
    yellow 0°

Such values make the three dark halftone dots form an equilateral triangle. This, in turn, creates the effect of the circular distribution of the dots. The yellow, light one, creates a moire effect, but as this color is light it does not affect the effect adversely.

5. Now the mundane part. Repeat this process for every file, converting the proper channels and using respective angles for each color. This should produce four black-and-white files with halftones based on each basic CMYK color. You may want to keep the black converted to 50% threshold, however, to make it opaque.

6. Convert all the files to grayscale with a 1:1 size ratio.

Select color range — black with 200 fuzziness.

Now use Ctrl/Ccmd+J to paste the selection as a layer and remove the background.

Do this for all four files. We now have four halftones with transparency.

7. Drag all these files into a new one as separate layers. Remember to create a fresh CMYK file as converting them before has changed sizes and resolutions. Name all the layers the same as the input files: C, M, Y, and K, to keep track of color halftones to fill in. Leave the background fully white. Keep blacks on top.

8. Block each of C, M and Y layer’s transparency and fill the layer with proper color, e.i. fill the lowest one with cyan, then magenta, then yellow and the top one should be left black.

All the halftones are ready now.

9. Set layer modes to multiply for color layers, black can stay on normal. If you use black halftone instead of solid black and put it on the bottom, you will achieve the poor old print effect.

10. You’re welcome.
