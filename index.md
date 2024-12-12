# std::cout << "Hello, World"

Hello. My name is Erasmo Alcazar, and I am currently a student at [Cal State Fullerton](http://www.fullerton.edu/). My major is Computer Science.

### CPSC 120

* Lab 10
    
    One of the most enjoyable computer science labs that I worked on was lab 10, Part 1 The reason that I liked the lab is because of the premise which was writing "a program that will create a two-dimensional data structure from `std::vector` to organize California's population data by county". In this lab, I was able to write a function that loops through a 2D vector and pulls out the name of each county.

    visual representaion:
    ```C++
    std::string AllCountiesString(const std::vector<std::vector<std::string>>& counties) {
      std::string all_counties_string;

      for (const auto& countie : counties) {
        all_counties_string += countie.at(0) + " ";
      }

      return all_counties_string;
    }
    ```

    ![Test](./home/erasmo/Eraz-wq.github.io/render1733981402984.gif)

#### Computer Science Projects
Github page link: [https://github.com/Eraz-wq](https://github.com/Eraz-wq)