---
layout: post
title: "블록 요소(block element) & 인라인 요소(inline element)"
date: 2022-09-07 23:32:05 +0900
toc: true
toc_sticky: true
categories: html-css
---

# 블록 요소(block element) & 인라인 요소(inline element)


## 🧸 블록 요소(block element)
<br>

### 1. 블록 요소 종류   
* div
* p
* form
* h1 ~ h6
* header 등등등...

<br>

### 2. 블록 요소 특징

 - 사용 가능한 최대 가로 너비 사용
 - margin, padding (위,오른쪽,아래,왼쪽) 다 사용가능 
 - 다음 태그는 다음 줄에 표현
 - 또 다른 block요소와 inline요소도 포함가능
 - 레이아웃을 위한 용도로 사용

<br>

<hr>
<br>

## 🧸 인라인 요소(inline element)
<br>

### 1. 인라인 요소 종류   
* a
* img
* span
* input
* em 등등등...

<br>

### 2. 인라인 요소 특징

 - 좌우 공간 필요한 만큼 차지
 - 한 줄에 여러요소 포함가능 
 - margin, padding의 상하 값 가질수 없음 
 - 너비, 높이 값 가질 수 없음

<br>

<hr>
<br>

## 🧸 인라인 블록 요소(inline-block)
<br>

### 1. 인라인 블록 요소 종류   
* img
* input
* button
* select 등등등...

<br>

### 2. 인라인 블록 요소 특징

 - inline처럼 줄바꿈없이 정렬되지만, margin padding 속성의 상하 간격 지정 가능
<br>

   <hr>
   <br>

📌 이 코드로 인라인블록 요소 적용 가능
```css
input {
   position:absolute;

   position:fixed;
}
```


📌 블록요소 -> 인라인요소
```css
span  {
display: inline;
}
```
<br>

📌 인라인요소 -> 블록요소

```css
p  {
display: block;
}
```

<br>

<hr>

<br>

## 🔑&nbsp;키워드 

### 1. inline 태그 5개를 일렬로 나열   

- 줄바꿈이 없으면 한줄에 여러 요소 나열

<br>

### 2. block line 태그 5개를 일렬로 나열

- 줄바꿈이 자동으로 일어나 수직으로 나열

<br>

<p align="center">
<img  width="500px" src="https://miro.medium.com/max/1400/1*AFeOAqXNJJdfYAjfXiJ9AQ.jpeg"> 
</p>

[출처](https://codeburst.io/block-level-and-inline-elements-the-difference-between-div-and-span-2f8502c1f95b)