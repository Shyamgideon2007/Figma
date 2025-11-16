# Ex09 Event Registration Web Application
## Date: 16-11-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```

<div style="width: 390px; height: 844px; position: relative">
  <div style="width: 390px; height: 844px; left: 0px; top: 0px; position: absolute; background: #F5F5DC; overflow: hidden">
    <img style="width: 378.98px; height: 57px; left: 7px; top: 30px; position: absolute" src="https://placehold.co/379x57" />
    <div style="width: 363px; height: 145px; left: 18px; top: 251px; position: absolute; color: black; font-size: 20px; font-family: Istok Web; font-style: italic; font-weight: 700; word-wrap: break-word">FULL STACK DEVELOPMENT <br/><br/>                                           <br/>                    Dr. SUGESHAN    <br/>                                       BE (CSE)                                                     </div>
    <div style="width: 354px; height: 37px; left: 18px; top: 472px; position: absolute; color: black; font-size: 40px; font-family: Irish Grover; font-weight: 400; word-wrap: break-word">Learn and Earn</div>
    <div style="width: 342px; height: 161px; left: 28px; top: 620px; position: absolute; color: black; font-size: 40px; font-family: Italiana; font-weight: 400; word-wrap: break-word">Enjoy learning through gamified learning model</div>
    <div style="width: 100px; height: 100px; left: 268px; top: 429px; position: absolute"></div>
  </div>
</div>

import React from "react";
import styled from "styled-components";

const StyledLogo1 = styled.div`
  width: 378.98px;
  height: 57px;
  left: 7px;
  top: 30px;
  position: absolute;
`;

const StyledFullstackdevelopmentdrsugeshanbecsespan = styled.span`
  color: black;
  font-size: 20px;
  font-family: Istok Web;
  font-style: italic;
  font-weight: 700;
  word-wrap: break-word;
`;

const StyledLearnandearnspan = styled.span`
  color: black;
  font-size: 40px;
  font-family: Irish Grover;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledEnjoylearningthroughgamifiedlearningmodelspan = styled.span`
  color: black;
  font-size: 40px;
  font-family: Italiana;
  font-weight: 400;
  word-wrap: break-word;
`;

const StyledFrame2 = styled.div`
  width: 100px;
  height: 100px;
  left: 268px;
  top: 429px;
  position: absolute;
`;

const StyledIPhone13141 = styled.div`
  width: 390px;
  height: 844px;
  left: 0px;
  top: 0px;
  position: absolute;
  background: #F5F5DC;
  overflow: hidden;
`;

const StyledFrame1 = styled.div`
  width: 390px;
  height: 844px;
  position: relative;
`;

export const Frame1 = () => {
  return (
    <StyledFrame1>
      <StyledIPhone13141>
        <StyledLogo1  src="https://placehold.co/379x57"/>
        <StyledFULLSTACKDEVELOPMENTDrSUGESHANBECSE>FULL STACK DEVELOPMENT <br/><br/>                                           <br/>                    Dr. SUGESHAN    <br/>                                       BE (CSE)                                                     </StyledFULLSTACKDEVELOPMENTDrSUGESHANBECSE>
        <StyledLearnandEarn>Learn and Earn</StyledLearnandEarn>
        <StyledEnjoylearningthroughgamifiedlearningmodel>Enjoy learning through gamified learning model</StyledEnjoylearningthroughgamifiedlearningmodel>
        <StyledFrame2 />
      </StyledIPhone13141>
    </StyledFrame1>
  );
};

```

## OUTPUT:

<img width="1477" height="836" alt="Screenshot 2025-11-17 005530" src="https://github.com/user-attachments/assets/95a4b5f0-076d-46dd-82ef-363318f8ddc7" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
