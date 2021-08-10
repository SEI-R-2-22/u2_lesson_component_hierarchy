# Component Hierarchy Diagrams

## Overview
A component hierarchy diagram is a useful tool in planning a React application with various interconnected components. This diagram can help you map out which components you need to build, and where you need to put them in your code.

Disclaimer: The abbreviation CHD is not an industry practice. If you say "I have a CHD," in an interview, you will get strange looks.

## Objectives
- Learn what a component hierarchy diagram is, and why it is useful in planning React app development
- Review examples of a diagram for a social media site

## Why Use a CHD?
React Review:
One of the benefits of React is the Virtual DOM, which allows us to target specific portions of a page for smaller updates rather than rerendering the entire page with every small change. In order to make the most of this, it is best practice to break down your application into smaller, reusable components that pass props to each other. 

As your applications become more complicated, the list of components gets longer, and it gets increasinglyy difficult to keep track of all of the pieces in your brain. A component hierarchy diagram (aka component level diagram) can be used to visualize where all the pieces fit.
