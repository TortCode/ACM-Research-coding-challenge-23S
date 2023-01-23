# Distinguishing features of stars analysis (Spring 2023)

Please note that the star type, denoted as integers, are translated as the following:
- Brown Dwarf -> Star Type = 0
- Red Dwarf -> Star Type = 1
- White Dwarf -> Star Type = 2
- Main Sequence -> Star Type = 3
- Supergiant -> Star Type = 4
- Hypergiant -> Star Type = 5

---

## Traditional Hertzsprung-Russell (HR) Diagram

The standard diagram used to display the categories of stars is the HR diagram which plots temperature against luminosity of a star. It is shown below for the given dataset.

![full_hr](https://user-images.githubusercontent.com/44101297/214127455-358f40d8-e882-4106-bf61-7806d7397cac.png)

From this diagram it is hard to distinguish supergiants from hypergiants and also brown dwarves from red dwarves, so we need to look for better properties to distinguish these classes. 

## Giants Analysis

We analyze the correlations between various properties when only giants are considered and obtain the following table.

![giants_corr](https://user-images.githubusercontent.com/44101297/214140567-a0cb212f-27b0-4087-bc06-ff5a88d590a5.png)

From this table, absolute magnitude and radius appear to correlate well with star type. We plot the results below, which show that radius is an excellent distinguishing property, with absolute magnitude being acceptable.

![giants_plot](https://user-images.githubusercontent.com/44101297/214141066-1c7d681c-4bc2-4a9f-9b6e-f2f6eae086fb.png)

## Dwarves Analysis

Now we turn our attention to dwarves. The results of their correlations are below.

![dwarves_corr](https://user-images.githubusercontent.com/44101297/214141286-647302d2-442c-4320-9fb4-815ef5af8967.png)

Again, absolute magnitude and radius are good properties to investigate. Plotting all dwarves, absolute magnitude looks like an excellent indicator of type.

![dwarves_plot](https://user-images.githubusercontent.com/44101297/214142891-d024f34c-312b-49bc-9aad-49927bdec36e.png)

## Final Results

Both of these unusual categories are distinguished well via radius and absolute magnitude. We plot these two properties for the entire dataset below.

![absmag_rad_plot](https://user-images.githubusercontent.com/44101297/214143274-ba603d46-c3b6-48b3-8544-83cc4c7ac7e4.png)

Absolute magnitude and radius divide the entire dataset beautifully into rectangular portions for each type. These two features contain all the information needed to categorize stars into different types. 
A simple decision tree could be trained on these features to classify stars.





3. Replace this README file with a description ([written in Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)) of your solution. Regardless of your success, describe the problem you set out to solve and how you did it. Split it up into sections with headers, and, if relevant, include figures.
