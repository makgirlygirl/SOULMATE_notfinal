# SOULMATE_final

> Ewha Womans University Cyber Security Engineering Graduation Project
> 
> MakgirlyGirl | Yoonseo Kim, Seohyon Park, Hongeun Ahn, Yujin Chang

 - SOULMATE is a self-directed learning service that helps you study English alone without private education.
 - AI-based self-directed learning service that creates questions of the Korean-SAT type.
 
 - Eliminating educational inequality by providing free educational opportunities to the underprivileged in private education.
 - User-tailored English learning using real-time problem production.


## Table of Contents
 
- [Development Environment](#Development-Environment)
- [Service Structure](#Service-Structure)
  - [Question bank Generation](#Question-bank-Generation)
  - [Real-time Question Generation](#Real-time-Question-Generation)
<!-- - [Description](#Description)
  - [Model](#Model)
  - [Frontend](#Frontend)
  - [Backend](#Backend) -->
- [Demonstration](#Demonstration)  
  - [Video](#Video)
  - [Generated Questions](#Generated-Questions)

## Development Environment
![ㅇ](https://user-images.githubusercontent.com/65396560/204125126-9b359837-d020-4ab1-a0b3-2758a671e957.png)

Create a virtual environment with all requirements.

```shell script
conda env create --file SOULMATE_env.yaml
```


## Service Structure

### Question bank Generation
- Create Question bank
 ![문제은행1 크게](https://user-images.githubusercontent.com/65396560/204124810-2b1168e1-df24-4b05-ade2-833c20952c8a.jpeg)
- When user use service
 ![문제은행22 크게](https://user-images.githubusercontent.com/65396560/204124819-0d7cb398-f4d0-4fee-9d67-aae817c3b7f4.jpeg)

### Real-time Question Generation
- When user use service
![실시간 크게](https://user-images.githubusercontent.com/65396560/204124826-9bc4a6be-7899-4417-abcf-5839de5fcac2.jpeg)

## Demonstration

### Video
- [Youtube link](#youtubelink)

### Generated Questions
- SOULMATE Question bank
  - Search for problems already stored in the SOULMATE database by type.
  
- Real-time Question Generation
  - If you enter your passage, SOULMATE AI will create a new Korean-SAT type questions.

- Problem Solving Screen (Question bank/Real-time Question Generation)
  - Solving questions and grading
  - Save as .docx format
  - Report the wrong questions

