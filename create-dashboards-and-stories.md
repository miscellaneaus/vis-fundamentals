[<-- Back to Main Page](README.md)<a name="top"></a>
# Create Dashboards and Stories
<hr>

# Building a dashboard<a name="1"></a>

#### [^ back to top of page](#top)
# Creating interactive dashboards using actions<a name="2"></a>


#### [^ back to top of page](#top)
# Refining a dashboard<a name="3"></a>
## 1. Refine for placement and layout
As you create your dashboard, you'll want to ensure that the sheets and other elements are sized and positioned correctly. This lesson lists some areas to check and refine.
### Start with the layout
#### SELECT WORKSHEETS TO INCLUDE
Decide which worksheets you want to include in your dashboard and make sure that each worksheet you want to use has a title. You don't have to show the title, but it's easier to select the correct worksheet when it has a meaningful name. Make sure that the view with your key finding or main question is placed in the most prominent spot. 

Note: You can easily see a list of where a worksheet is being used within the workbook by right-clicking the worksheet tab and selecting Used in.

The dashboard below uses Profit by State as its most prominent view.
![image](https://user-images.githubusercontent.com/95596079/144782299-27299c26-3d41-4867-b0ea-91a7c61ae3e4.png)

#### SET THE LAYOUT ORIENTATION WITH CONTAINERS
Layout containers allow you to set the orientation of the items in your dashboard. A Horizontal layout container resizes the width of the views and objects it contains; a Vertical layout container adjusts height. 

When you drag worksheets into a dashboard, the size and layout are typically fixed by default. Use layout to create a definition within your dashboard, and then fine-tune the placement and position of the worksheets. 

Be aware that items within the same layout container can resize and change position when users interact with the dashboard. These changes help minimize extra white space within the container.
![image](https://user-images.githubusercontent.com/95596079/144782361-d61207ec-321b-4950-825a-1218d61b861d.png)

#### USE NON-WORKSHEET OBJECTS
You can use non-worksheet objects to further customize your dashboard.
![image](https://user-images.githubusercontent.com/95596079/144782409-c3775c39-6ba1-4976-b20f-21f4f772f5ee.png)

#### CONSIDER FLOATING A VIEW
To save space or improve its proximity to another item, you can float a view, filter, legend, text, image, web page, or even a layout container. For example, you have grouped a set of key performance indicators into a container. By floating that container, you can save space by strategically layering the floating container over an appropriate location on the dashboard.

You can also add a button object to floating containers (Vertical or Horizontal) that will enable you to toggle between showing and hiding them. This feature enables you to save space when dashboard elements (filters, legends, views, and so on) do not need to be visible at all times.

The following dashboard uses a floating view for the color legend to help users relate colors to both views.
![image](https://user-images.githubusercontent.com/95596079/144782464-10fbfbd5-f75b-449d-94ad-d55014ae36f1.png)

#### ADD WHITE SPACE
White space helps to align and separate objects. Add white space using one of the following methods:
- Insert and resize a blank container.
- Adjust either the outer or inner padding of a view, container, or object.

Padding lets you precisely space items on a dashboard, while borders and background colors let you visually highlight them. 

Inner Padding sets the spacing between item contents and the perimeter of the border and background color; Outer Padding provides additional spacing beyond the border and background color.
![image](https://user-images.githubusercontent.com/95596079/144782498-f27e2a08-d317-4bd4-8fdd-30810589123c.png)

#### USE BORDERS AND BACKGROUND COLORS SPARINGLY
It is easy to add too many visual elements, which in turn will distract rather than enhance the dashboard experience.

### Determine the device layout (Tableau Desktop Only)
After you have built a dashboard, you can create layouts that are specific to particular devices. Dashboards can include layouts for different types of devices that span a wide range of screen sizes. When you publish these layouts to Tableau Server or Tableau Online, people viewing your dashboard experience a design optimized for their phone, tablet, or desktop. As the author, you only have to create a single dashboard and deliver a single URL.

The following video shows how to adjust your dashboard's appearance for specific device layouts.

```Customizing your dashboard for a specific device```

## 2. Refine for instructional clarity
How do you help your audience so they can immediately understand the purpose of your dashboard and how to use it? Careful use of instructional text and titles gives your users instant directions on how to use the dashboard.
### Instructions and annotations
Adding instructions to your dashboard enhances and guides the user experience, especially when you want users to interact with your view. Here are some tips for adding instructions.
- Use titles on filters in the view to provide direction to users. All filters have titles you can edit using the drop-down menu on the filter. For example, Region is the dimension used to create this filter. Rename the filter so it reads as an instruction to a user.
- ![image](https://user-images.githubusercontent.com/95596079/144782985-d1ac861a-c34f-4709-ac09-befd40948356.png)
- Add text boxes with instructions on how to read the elements in your dashboard, especially if you are sharing data that is not familiar to your audience.
- Use a common font color, size and style for all instruction text. (See highlighted areas in the example below.)
![image](https://user-images.githubusercontent.com/95596079/144783089-90a8bcd6-273a-460a-9c9b-e67f091bad67.png)
- Use annotations to call attention to interesting data points, but sparingly. Edit the default annotation text so it reads well.
![image](https://user-images.githubusercontent.com/95596079/144783105-576bab16-2d92-4755-8c45-17aa3b2ab404.png)

The following video shows how to create instructive text to guide users. 

```Using instructions and annotations to guide users```

## 3. Improve appearance and readability
There are many simple changes you can apply to dashboards that dramatically improve their appearance and readability. Assess your dashboard carefully. Does the data stand out clearly on its own? Is the dashboard too busy, with too many marks and details?
### Color, sizing and fonts
Use of appropriate colors, sizing, and fonts are one of the simplest and basic changes that you can make to improve the usability of any dashboard. These aspects form the visual foundation of your dashboard. Review these items to improve the appearance of a dashboard.
#### COLOR
- Limit total number of colors used.
- Reserve brightest colors (or any color) for the most relevant data points.
- Using two shades of the same hue (such as light blue and dark blue), suggests a relationship, especially if you are using other colors as well. If you don’t want to associate those items, assign them different colors. 
- Consider carefully whether adding borders or background colors helps focus attention or increases the visual clutter.
#### SIZING
- Keep your users' screen size in mind.
- When using crosstabs, don't use Fit Entire View; use a combination of a scroll bar and either Fit Width or Fit Height.
- To resize elements, try Shift+drag. (For example, use this if you have a 4-quadrant dashboard and want to resize the bottom-left quadrant without resizing the upper-right quadrant.)
- When resizing individual worksheets, use CTRL and the arrow keys to resize rather than manually dragging.
#### FONT
- Make the fonts readable and sized appropriately. Use fonts that optimize online readability.
- Make the font consistent as much as possible.

The quickest way to make a fast, large-scale change to all the titles in your dashboard is to change them at the workbook level. A workbook is the largest possible container for formatting settings.
1. Click **Format**, and then select **Workbook**.
2. Make your changes under **Fonts**, in the **Format Workbook** pane.

The following image shows how the fonts have been set to Century Gothic and the font color to turquoise.
![image](https://user-images.githubusercontent.com/95596079/144784033-ccd79420-6767-4374-aae4-ebf79ddd2ce0.png)

### Tooltips
Once you are done with the main design work, review your tooltips. Tooltips reinforce the story you’re trying to tell with your dashboard. They also add helpful context to your view. Tableau populates a view’s tooltips automatically, but you can easily customize them by clicking Worksheet > Tooltip. Just like you want to put your most important view in the upper left of your dashboard, you want the most important elements of your tooltip to be at the top. 

Watch the video below to learn how to use tooltips to emphasize important information in a dashboard.

```Using tooltips to emphasize important information in a dashboard```

### Grid lines and shading
It's a good practice to remove unnecessary grid lines or shading within views, which can be distracting for your user. 

Consider the example of the dashboard shown here. Review the dashboard and answer the questions below.
![image](https://user-images.githubusercontent.com/95596079/144784152-97549683-1a01-4167-b5b3-c876e8d76435.png)

_What do you notice about the grid lines in the **Plot of Sales Profits** view?_
- _Are the grid lines necessary for understanding the view?_
- We don't really need them to help us see interpret this data, and they stand out in a distracting way.

_What about shading in the Profitability Details view?
- _Is the shading in the view serving a useful purpose, or does it just make the view look busy?_
- The view already has some shading to distinguish between the rows. The extra shading isn't necessary.

The good news is that it is easy to remove grid lines and shading that are visually distracting by using the Format option.
1. Select the worksheet that uses the grid lines, click the **Format** menu, and then select **Lines to remove grid lines from the rows in the worksheet**.
![image](https://user-images.githubusercontent.com/95596079/144784411-c44b961b-4ac8-47d5-adaf-d9a27c4c1dad.png)
2. To remove shading from a worksheet, use the **Format** menu, and select **Shading**.
![image](https://user-images.githubusercontent.com/95596079/144784446-3d1dabc7-eb39-4129-9f82-a8c0250ed37f.png)

4. Now, the dashboard looks less cluttered with the grid lines and shading removed.
![image](https://user-images.githubusercontent.com/95596079/144784469-2e0857c6-4087-4133-9f13-472f225f1aa2.png)

## 4. Add visualizations in tooltips
As you create views and look for ways to reveal more details about data to your audience, consider using a view in the tooltip to give the user more information without cluttering the dashboard. 

Showing related vizzes in tooltips helps your users engage with the data at a different or deeper level, while keeping them in the current context and maximizing the space available for the current view.

The following example shows how the viz in tooltip feature allows you to quickly see the sales data for each country within a region.
![image](https://user-images.githubusercontent.com/95596079/144784603-f58dd678-4b50-4584-856c-41f38671df96.png)
### Add a viz in tooltip
To place a viz in a tooltip:
1. From the main (source) viz, click **Tooltip** on the **Marks** card.
2. Click **Insert**, and then select **Sheets**.
![image](https://user-images.githubusercontent.com/95596079/144784659-6ca0d6b0-90b1-43c9-9189-f43a6122cdd1.png)
3. Select the target sheet that should appear in the tooltip, and click **OK**. Now when we hover over a mark on the source viz, the tooltip displays the target viz.

The following video shows how to use a viz on tooltip to show sales of products in each category for individual countries.

```Adding viz in a tooltip```

### Did you know?
#### You can set the size of a view in a tooltip.
When you create a viz in tooltip, you want to consider the size. If the target viz is too large, the tooltip will indicate “view is too large to show”. By default, the target viz is 300 by 300 pixels. You can edit the tooltip to manually change the size, but be careful that resizing doesn’t detract from the main visualization.
![image](https://user-images.githubusercontent.com/95596079/144785133-02f28723-0404-4c4f-bc66-d4d9eefd843d.png)

#### The view in the tooltip is always static.
The viz in the tooltip is a static image, not an interactive viz. A viz in tooltip cannot have its own viz in tooltip. Multiple target sheets can appear in the same tooltip. 
![image](https://user-images.githubusercontent.com/95596079/144785156-f844f5ba-4499-4695-80f0-cad21be98337.png)

#### It's possible to format tooltip text.
You can get creative with text formatting in the tooltip. In the example below, the target viz has three colors, representing **Technology**, **Office Supplies**, and **Furniture**. Each label is set to its corresponding color, functioning as a color key.
![image](https://user-images.githubusercontent.com/95596079/144785171-92005db2-58a0-42fe-ac88-31a52cfa06da.png)

#### Hovering on a mark filters the target viz.
On the sheet for the target viz, you can see two things. One, the viz as it appears is much larger than in the tooltip, and two, there is a “tooltip” filter on the Filters shelf. When a tooltip containing a viz is displayed, the target viz is filtered based on the mark you're hovering over.
![image](https://user-images.githubusercontent.com/95596079/144785192-52f520da-c97a-41fa-bdaf-78f44c8bf608.png)

#### Show me resets the tooltip.
If you use **Show Me** in the source sheet to change the view structure, you will reset all tooltip edits, including Viz in Tooltip references. To reverse this, you will need to reconfigure the viz in the tooltip.

## 5. Add and format animations in a visualization
With Tableau viz animations, it’s easier than ever to present data that shows changes. You can animate visualizations to better highlight changing patterns in your data and direct your audience’s focus to what matters the most.

Without animations, changing something like a date filter causes scatterplot marks to suddenly jump to new locations. It’s difficult to pinpoint what changed or why, but a smooth animation connects the dots. You can spot and understand changes, such as when a specific mark becomes an outlier, when there’s a sudden value spike or dip, or when data clusters appear. 
### Types of animations
In Tableau, you can choose between two different styles of animations: simultaneous or sequential.

#### SIMULTANEOUS
The default simultaneous animations are faster and work well when showing value changes in simpler charts and dashboards.
![SFzbz-34Nx9dxv7h_5WpimRfiORc0ZmBj](https://user-images.githubusercontent.com/95596079/144785516-2eec5834-b552-4172-b0bf-24e5882790b5.gif)
#### SEQUENTIAL
Sequential animations take more time but make complex changes clearer by presenting them step-by-step.
![J7kZE8seyQPnF-Us_JEy_Zo_v_2MYklQq](https://user-images.githubusercontent.com/95596079/144785579-f4bc1dd4-3a8b-47af-a04f-29e3adc3a354.gif)

### Authoring animations
Animations can be configured for entire workbooks down to individual sheets. This is especially useful when applying different settings to multiple vizzes in one dashboard. 

To create an animation:
1. From the menu, select **Format**, and then click **Animations**.
2. If you want to animate every sheet, under Workbook Default, click On. Then do the following:
    - For **Duration**, select a preset, or specify a custom duration of up to **10** seconds.
    - For **Style**, select **Simultaneous** to play all animations at once , or **Sequential** to fade out marks, move and sort them, and then fade them in.
    - ![image](https://user-images.githubusercontent.com/95596079/144785823-eba2c3ad-dea8-4e25-9d60-5c69e89cd536.png)
3. To override workbook defaults for a particular sheet, change the settings under **Selected Sheet**.
    - ![image](https://user-images.githubusercontent.com/95596079/144785859-c330ccfc-c11e-4957-8b9c-d06b1439f512.png)

Tableau allows you to animate a broad variety of vizzes. Once on, viz animations automatically work for any underlying data changes. However, the following Tableau features don't animate:
- Maps, polygons, and density marks in web browsers
- Pie and text marks
- Axes and headers
- Forecasts, trends, and reference lines
- Page history trails (If a viz includes these, turn off animations to avoid unexpected behavior.)

## 6. Try it! Refine and format a dashboard
### Scenario
A colleague has asked you to review a dashboard to see if it’s customer-ready. Improve the dashboard, paying specific attention to instructions, tooltips, color, arrangement, and fonts.

When you are done, your dashboard should look like the following. 

Good luck!
![image](https://user-images.githubusercontent.com/95596079/144786310-280a07a7-269b-4e55-ada6-ca672665b383.png)

### Download the file below to use with this activity
<img src="assets/File Icon Spaced.svg" height="20"/><a id="raw-url" href="https://raw.githubusercontent.com/miscellaneaus/vis-fundamentals/main/assets/9/improve_a_dashboard's_design_starter.twbx">improve_a_dashboard's_design_starter.twbx</a><br>

### Follow the steps below to complete this activity
- The **Expected** **result** shows the view at the end of the step.
- The **Hint** provides additional guidance to complete the step.
1. Open the starter file in Tableau.
2. Add instructions to the Coffee Chain Profit Analysis view, similar to those used for the **Superstore Profit Analysis** view.
    - Expected Result
    - ![image](https://user-images.githubusercontent.com/95596079/144786618-0bc61d4d-379c-447c-8454-207fac44d6b2.png)
    - HINT:
    1. Double-click the **Coffee Chain Profit Analysis** text.
    2. Below <Sheet>, type Orange is a missed goal. Click to filter the view below. (Note: You will change the color of the marks in a later step)
    3. Click OK.
 
3. Change the font and colors of the dashboard titles. Change the font of all worksheet titles to **Arial** and the color of the dashboard title from blue to black.
    - EXPECTED RESULT:
    - ![image](https://user-images.githubusercontent.com/95596079/144786872-bba35b15-5902-4abe-bd4e-cecd11a40cf9.png)

    - HINT:
    1. Click Format and then select Workbook.
    2. Under Fonts, click the drop-down arrow for Worksheet Titles.
    3. Next, click the drop-down arrow next to the font Calibri.
    4. From the list, select Arial.
    5. Click the field again to close the drop-down list.
    6. Next, click the drop-down arrow next to Dashboard Titles.
    7. From the colors palette, select black and click the field again to close it.
    8. Close the Format Workbook pane.
    
4. Move the **Region Selection** filter to a more prominent position under the dashboard title **Profit Analysis**. 
    - EXPECTED RESULT:
    - ![image](https://user-images.githubusercontent.com/95596079/144786887-fa2a0572-3e9c-40ec-a6cb-4dd7c10fe818.png)

    - HINT:
    1. Select the **Region** view and place it below the **Profit Analysis** title.
    2. Adjust and resize the window so the filter takes up minimal vertical space but is still large enough to show all content.
5. Revise the colors for the **Coffee Chain Profit Analysis** sheet to match the colors in the **Superstore Profit Analysis** sheet.
    - EXPECTED RESULT:
    - ![image](https://user-images.githubusercontent.com/95596079/144786897-4e2941e1-ec68-4652-b02b-2a941d5434c3.png)

    - HINT:
    1. Open the Coffee Chain Profit Analysis worksheet.
    2. Click Color on the Marks card.
    3. Click Edit Colors.
    4. In the Select Data Item area, click False and then click orange.
    5. In the Select Data Item area, click True and then click gray.
    6. Click OK.
  
6. On the **Coffee Chain Profit Analysis** worksheet, add **Product Name** to the tooltip as a dynamic field.
    - EXPECTED RESULT:
    - ![image](https://user-images.githubusercontent.com/95596079/144786915-34a3d297-5181-4511-8b25-a3bf32dec5b3.png)

    - HINT:
    1. Click the Coffee Chain Profit Analysis worksheet tab
    2. On the Coffee Chain Profit Analysis worksheet, click Tooltip on the Marks card.
    3. At the top of the text box, press the ENTER key to create a new space.
    4. Type Product: and format it the same as the other text.
    5. Place the cursor at the end of Product: and click Insert.
    6. Select Product from the drop-down list.
    7. Click OK.

Click the Profit Analysis dashboard tab to view your changes.
### Knowledge check
In the last step of this activity, you added a dynamic field to the tooltip. Why?
- [ ] To make the information complete.
- [ ] To show the actual profit ratio.
- [ ] To show the product name.
- [ ] To show and reflect the current product name.

ANSWER: To make the information complete.


#### [^ back to top of page](#top)
# Telling stories with data<a name="4"></a>
## 1. Introduction to Tableau stories

A story is a sheet that contains a sequence of views and dashboards that work together to convey information. You can use stories to make a compelling case by showing how analytical insights are connected. 

Since a story is a sheet, the methods you use to create, name, and manage worksheets and dashboards also apply to stories. Each individual sheet in a story is called a story point.

When you share a story — for example, by publishing a workbook to Tableau Public, Tableau Server, or Tableau Online — users can interact with the story to reveal new findings or interact with data.

Since a story is a sheet, the methods you use to create, name, and manage worksheets and dashboards also apply to stories. Each individual sheet in a story is called a story point.

When you share a story —for example, by publishing a workbook to Tableau Public, Tableau Server, or Tableau Online—users can interact with the story to reveal new findings or interact with data.

Watch this one minute introduction to learn about using stories in Tableau.

```Using stories in Tableau```
    
As shown in the video above, you can create stories to tell a data narrative, provide context, demonstrate how decisions relate to outcomes, or simply make a compelling business case. 

### Best practices for telling great stories

A good data story brings data and discoveries to life. Use the following best practices when creating a story:
#### Know the story's purpose
Before you build your story, take some time to think about the purpose and what you want your viewers’ journey to be. Is it a call to action, is it a simple narrative, or are you presenting a business case? 

If you're presenting a case, decide whether you want to present data points that lead up to a conclusion at the end, or start with a conclusion, and then show the supporting data points. The latter approach works well for a busy audience.

Finally, sketching out your story first on paper or a whiteboard can help you quickly identify problems with your sequence.

#### Keep it simple
A common error is trying to cram too many views and dashboards into a single story. The result is too many points for your viewers to take in. The clarity of each story point is also important. 

Take a step back and consider your story from the perspective of someone who’s never seen it. Every element should serve a purpose. If captions, titles, legends, or grid lines aren’t necessary, get rid of them!

#### Plan for fast load times
The most wonderful story in the world won’t have much impact if it takes too long to load. People find long waits frustrating. Some of the most critical performance decisions you make begin before you even create your first view or story, in the data preparation stage.

#### Use 'Fit to' in your dashboards
Dashboards are a common ingredient in Tableau stories. For dashboards that you plan to include in your story, use the Fit to option under Size on the Dashboard pane. It will resize your dashboard so that it’s the right size for the story you’re creating.

## 2. Steps in creating a story
As you learned previously, stories show how facts are connected, and how decisions relate to outcomes. When you create a story, each story point can be based on a different view or dashboard, or the entire story can be based on the same visualization seen at different stages. You can then publish your story to the web, or present it to an audience.

When creating a story, use the following sequence of steps.

## 3. Create a story
Now that you are familiar with the overall process of creating a story, let’s learn how to create one. First, let’s look at the story workspace and the features available to create a story in Tableau.

## 4. Format a story

## 5. Try it! Create and format a story


### FILES
<img src="assets/File Icon Spaced.svg" height="20"/><a id="raw-url" href="https://raw.githubusercontent.com/miscellaneaus/vis-fundamentals/main/assets/9/add_actions_to_a_dashboard_starter.twbx">add_actions_to_a_dashboard_starter.twbx</a><br>
<img src="assets/File Icon Spaced.svg" height="20"/><a id="raw-url" href="https://raw.githubusercontent.com/miscellaneaus/vis-fundamentals/main/assets/9/Building_a_Dashboard_Starter.twbx">Building_a_Dashboard_Starter.twbx</a><br>

<img src="assets/File Icon Spaced.svg" height="20"/><a id="raw-url" href="https://raw.githubusercontent.com/miscellaneaus/vis-fundamentals/main/assets/9/Telling stories starter.twbx">Telling stories starter.twbx</a><br>









#### [^ back to top of page](#top)
