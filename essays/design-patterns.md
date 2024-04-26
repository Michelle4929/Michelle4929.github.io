---
layout: essay
type: essay
title: "Recipe for Success: Design Patterns in the Kitchen"
# All dates must be YYYY-MM-DD format!
date: 2024-04-25
published: true
labels:
  - Design Patterns
  - Programming
  - React
---

## My First Year Coding

  As I started on my coding journey, I was filled with excitement and curiousity, ready to explore all the different possibilites of programming. However, like most beginners, we make mistakes and are hesistant with each step forward. As my confidence was not present, I approached each problem with a sense of improvisation and messy solutions that seemed to work at the moment. My code obviously lacking in cohesion and clarity but my naive self unable to recognize the difference. Particulary when it came to design pattern, there was no discernible structure to guide the flow of words. As I repeat the same functions, not realizing there is a general repeatable solution to a commonly occuring problem. Even though I was unaware of the knowledge of design patterns, as I continue my journey with coding, my codes start to have a structural pattern. Although my attempts to incorporate these patterns are often clumsy and definitely leaves room for improvement, with each new project, I can see improvements in my coding practices. In my recent project, making a study application for UHM ICS students to self organize face-to-face groups, I noticed my code utilized some design patterns.
```
            <Card>
              <Card.Body>
                <SelectField name="day" options={generateDayOptions()} placeholder="Choose..." />
                <SelectField name="month" options={generateMonthOptions()} placeholder="Choose..." />
                <SelectField name="year" options={generateYearOptions()} placeholder="Choose..." />
                <SelectField name="startTime" options={generateTimeOptions()} placeholder="Choose..." />
                <SelectField name="endTime" options={generateTimeOptions()} placeholder="Choose..." />
                <TextField name="className" placeholder="ex. ICS 314" />
                <LongTextField name="description" placeholder="Anything else you would like to specify." />
                <HiddenField name="ghAttend" value="" />
                <HiddenField name="ssAttend" value="" />
                <HiddenField name="owner" value="username" />
                <SubmitField value="Submit" />
                <ErrorsField />
              </Card.Body>
            </Card>
```
React's usage of JSX and components follows a pattern similar to the Factory Method pattern. When I wrote ``` <SelectField />, <TextField />, <LongTextField />```, etc., React acts as a factory that creates instances of these components.

```
const bridge = new SimpleSchema2Bridge(Sessions.schema);
```
The SimpleSchema2Bridge follows a bridge pattern. The pattern decouples an abstraction from its implementation, which is common in schema validation libraries where the bridge acts as an adapter between different schema formats and validation mechanisms.

## Design Patterns

  In a world if software development was like cooking, design patterns are like the secret ingredients that turn a boring bland code into a flavorful masterpiece. Design patterns help software engineers use typical solutions to commonly occurring problems. Similar to having recipes you can use to solve recurring issues but have the flexibility of changing the order and features of the dish! Although, there are many different types of design patterns, there are three main groups:

1) **Creational**: They abstract the instantiation process, making the system more independent on how its objects are created. It increases flexibiliy and reuse of existing code. Creational design patterns are like crafting the blueprint. Patterns that are placed in this category are factory, abstract, builder, prototype, and singleton. In the case of Singleton, in the kitchen, with only one spatula, it ensures that there's only one chef in the kitchen able to wield it. Just like how Singleton pattern limits the instantiation of a class to a single instance, the spatula ensures there can only be one chef that can flip the burger at one time.

     
3) **Structural**: Explain how to assemble objects and classes into larger structures while still keeping them flexible and efficient. They use inheritance to compose interfaces and find ways to ccompose objects to obtain new functionality. Some patterns in this category are adapter, bridge, composite, decorator, facade, flyweight, and proxy. Stepping back into the bustling kitchen with ingredients prepped and tools in hands. The decorator pattern allows you to layer on enhancements without altering the base ingredients but adding flavors and textures. Just as an artist adds layers of paint onto their canvas, the decorator pattern adds new features to your objects without sacrificing their core structure.
   
4) **Behavioral**: Is concerned with algorithms and the assignment of responsibilites between objects. They are most specifically concerned with communication between objects. These patterns characterize complex flow that's difficult to follow at run time. Some patterns in this category are chain of responsibiliy, memento, observer, mediator, iterator, state, strategy, template method, and visitor. One last look into the kitchen, your dish starts to take shape, and you realize that it's not just about the ingredients but how everything interacts. The observer pattern comes in as your taste tester, that keeps an eye on the cooking process and reacts to changes in real time, notifying the workers of any updates. The observer pattern facilitates communication between objects, ensuring they're on the same page even when the recipe changes.

<p align="center">
<img width="400px" src="https://media.licdn.com/dms/image/D4D12AQEuzLBqR-ZH1Q/article-cover_image-shrink_720_1280/0/1657662542373?e=2147483647&v=beta&t=42nZNep-CujWlaCeLuQflv28Fa-kP4SZ5N-XKpWswUI">
</p>
