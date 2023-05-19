# YouTube Dataset Analysis - MapReduce Design Patterns using Apache Hadoop, Pig, Hive

This project is a university group project completed for the Advanced Hadoop MapReduce Programming for Big Data Analytics course. The goal of the project is to analyze the YouTube open source API dataset using Apache Hadoop, Pig, and Hive, applying various MapReduce design patterns and big data analysis techniques.

![image](https://user-images.githubusercontent.com/57429405/125012988-10876b00-e039-11eb-8372-eb6d48e8bc24.png)

## Features

- Implemented Apache Hadoop big data framework, including HDFS and MapReduce design patterns, to analyze the YouTube dataset.
- Utilized Apache Pig, a data flow language built on top of Hadoop, to execute Pig Scripts for Big Data Analysis.
- Created a data warehouse using Apache Hive for further analysis.

## Problem Statement

The objective of this project is to analyze the YouTube dataset using Hadoop, Pig, and Hive based on different column fields in order to provide comprehensive insights into the data.

## Dataset Summary

The dataset used for analysis is available at the following URL: http://netsg.cs.sfu.ca/youtubedata/

The dataset includes the following information for each YouTube video (separated by '\t' in the data file):
- Video ID: an 11-digit unique identifier for each video
- Uploader: the username of the video uploader
- Age: the number of days between the date when the video was uploaded and Feb.15, 2007 (YouTube's establishment)
- Category: the category chosen by the uploader for the video
- Length: the length of the video in seconds
- Views: the number of views for the video
- Rate: the video rating as a float number
- Ratings: the number of ratings received for the video
- Comments: the number of comments received for the video
- Related IDs: up to 20 strings representing the IDs of related videos

## Implemented MapReduce Design Patterns

The project includes the implementation of various MapReduce programs and design patterns, including:
1. Filtering
2. Join Patterns
3. Data Organization
4. Summarization

## Analysis Performed

The dataset analysis includes the following tasks:

### MapReduce Analysis:
1. Calculating the maximum rating, total rating, and total comment count by Video ID
2. Calculating the moving rating average by Video ID
3. Determining the best YouTuber based on the number of videos uploaded
4. Finding the top 50 favorite YouTube videos
5. Counting the total number of YouTube videos by category
6. Implementing binning based on categories
7. Chaining the binning result to get the top 25 videos per category
8. Recommending followers based on connected followers
9. Determining the total views based on Video ID

### Pig Analysis:
1. Finding the top 5 categories of YouTube videos
2. Finding the top 10 rated YouTube videos
3. Finding the top 10 rated YouTube videos by categories
4. Finding the top 10 viewed YouTube videos
5. Finding the top 10 viewed YouTube videos by categories

### Hive Analysis:
1. Determining the top 10 channels with the maximum number of likes
2. Finding the top 5 categories with the maximum number of comments

## Visualizations

Visualizations for Pig analysis can be found at the bottom in the Pig analysis section of the project.


