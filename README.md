# Power Apps UI Components

## Component Library

Use components library to accelerate the speed of Power Apps development with high quality, by reusing the existing components assets and sharing with the team.

This component library is made for my daily POC projects, and you can use this as example or make your own library.

Hope this could be a good start point for you to quickly understand how components library can benefits your dialy low code development.

Components library includes:

- TopBanner
- UserBottomPanel
- ImageButton
- Tab
- GeneralTopBanner
- GeneralBottomPanel
- TopPanelWithWaffle
- Card
- GeneralCard
- KPICard
- UserProfileCard
- SearchBar

Sample app made with these components

**Home Screen**

![image-20220719211228608](image/README/image-20220719211228608.png)

**Detail Screen**

![image-20220719212014688](image/README/image-20220719212014688.png)



## Installation

- Download the solution in Release folder.
- Import solution into your environment.
- Use these componets in your solutions.

### TopBanner

![image-20220719184748769](image/README/image-20220719184748769.png)

### UserBottomPanel

![image-20220719184814149](image/README/image-20220719184814149.png)

### ImageButton

![image-20220719222936189](image/README/image-20220719222936189.png)

### Tab

![image-20220719223017904](image/README/image-20220719223017904.png)

### GeneralTopBanner

![image-20220719184939517](image/README/image-20220719184939517.png)

### GeneralBottomPanel

![1649355909739.png](image/README/1649355909739.png)

### TopPanelWithWaffle

![image-20220719223107315](image/README/image-20220719223107315.png)

### Card

![image-20220719222239206](image/README/image-20220719222239206.png)

### GeneralCard

![image-20220719215738817](image/README/image-20220719215738817.png)

### KPICard

#### Screen shot

![1649355971462.png](image/README/1649355971462.png)

#### Input properties

- Background Fill - Color
- KPI - Text
- KPI Color - Color
- KPI Font Size - Number
- KPI Font Weight - FontWeight
- Title - Text
- Subtitle - Text
- Title and Subtitle Font Size - Number
- Font Color - Color
- Subtitle Icon Image - Image
- Subtitle Icon Size - Number
- Show Icon Instead of Subtitle - Booleana
- Enable OnClick - Boolean

#### Behaviours

- OnClick - Boolean

#### Output properties

- N/A

### UserProfileCard

#### Screen shot

![image-20220719223152631](image/README/image-20220719223152631.png)

### SearchBar

#### Screen shot

![image-20220719185726497](image/README/image-20220719185726497.png)

#### Input propoerties

- Background Fill - Color
- Font Size - Number
- Font Weight - Text(Bold,SemiBold, Lighter)
- Search Hint - Text
- Button Color - Color
- Result Count - Number
- Show Search Result - Boolean
- Show Refresh Button - Boolean
- Show Add New Button - Boolean
- Show Sort Button - Boolean
- Show Searh Button - Boolean

#### Behaviors

- On Add New Clicked - Boolean
- On Refresh Clicked - Boolean
- On Search Clicked - Boolean

#### Output properties

- Srarch Text - Text
- Sort Order - SortOrder(Ascending/Descending)
