# React Native FlatList Performance Issue

This repository demonstrates a common performance issue encountered when using the FlatList component in React Native with large datasets. The application becomes slow, especially when updating the list.

## Problem
The FlatList's re-rendering process becomes inefficient with large datasets, causing performance degradation.

## Solution
The provided solution utilizes techniques like `keyExtractor`, `getItemLayout`, and potentially virtualization strategies to significantly improve the performance of the FlatList, particularly when handling numerous items.

## How to reproduce
Clone this repo and run the `FlatListBug.js` file. Observe the performance as you increase the amount of data.