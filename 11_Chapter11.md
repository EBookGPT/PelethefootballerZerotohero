# Chapter 11: Playing for the New York Cosmos

Welcome back, dear readers, to our journey of exploring the life of the legendary footballer Pele. In the previous chapter, we discussed the numerous setbacks and injuries that Pele faced during his illustrious career. But as they say, when the going gets tough, the tough get going. Pele was no exception.

After a brief stint with the Brazilian club, Santos, Pele retired from professional football in 1974. However, his thirst for the beautiful game was far from quenched. In 1975, Pele surprised the world by announcing his comeback and joining the New York Cosmos of the North American Soccer League (NASL). 

This move marked a new chapter in Pele's career as he became the highest-paid athlete in the world at the time and inaugurated a new era for professional soccer in the United States. New York Cosmos became the darling of American soccer, as Pele led them to multiple NASL championships. His arrival in the United States was the catalyst for the growth of soccer in the country, and his influence can still be felt in American soccer today.

And as if Pele's return wasn't enough to shake up the world of soccer, the New York Cosmos also welcomed a special guest, Franz Beckenbauer, one of the best defenders to grace the game. With Pele and Beckenbauer in the team, the New York Cosmos became a formidable force to be reckoned with.

As we delve deeper into this chapter, we will discuss Pele's experience playing for the New York Cosmos, his relationship with Franz Beckenbauer, and the immeasurable impact that his arrival had on American soccer.

So let's not waste any more time and get straight into the code that made Pele a success at the New York Cosmos!
# Chapter 11: Playing for the New York Cosmos - Exercises

Congratulations on reaching the exercise portion of this chapter, where we explore the code that made Pele a success at the New York Cosmos. Let's get right into it!

## Exercise 1: Conditioning and endurance

Pele returned to professional football after a brief hiatus, and it was clear that he had prepared himself physically to compete at the highest level. The NASL was a tough, physical league, and Pele knew he had to be in peak condition to make the most of his comeback. As such, he followed a strict conditioning and endurance routine, which included regular cardio workouts, strength training, and agility drills.

In this exercise, we will write a function to simulate Pele's conditioning and endurance routine. The function should take in a duration in minutes and return the number of calories burned performing cardio exercises for that duration.

```python
def burn_calories(duration):
    # Calorie burned per minute while performing cardio exercises
    calorie_burn_rate = 10 
    
    # Calculate the number of calories burned
    calories_burned = duration * calorie_burn_rate 
    
    return calories_burned
```

## Exercise 2: The Pele-Beckenbauer connection

One of the standout partnerships in the NASL was the duo of Pele and Franz Beckenbauer. Their on-field rapport was a crucial factor in the success of the New York Cosmos during their championship runs. 

In this exercise, we will write a function to simulate the Pele-Beckenbauer connection. The function should take in two lists, representing the passes made by Pele and Beckenbauer respectively. The function should return the number of successful passes completed between the two players.

```python
def pele_beckenbauer_connection(p_passes, b_passes):
    # Set to keep track of successful passes
    successful_passes = set()
    
    # Check each pass made by Pele and Beckenbauer
    for i in range(len(p_passes)):
        for j in range(len(b_passes)):
            # If the passes match and are successful, increment count
            if p_passes[i] == b_passes[j] and p_passes[i].is_successful: # assuming passes have 'is_successful' attribute
                successful_passes.add(p_passes[i])
    
    return len(successful_passes)
```

## Exercise 3: Impact on American soccer

Pele's arrival in the NASL had a significant impact on American soccer. He brought star power and international recognition to the league, attracting other world-class players and elevating the profile of soccer in the United States.

In this exercise, we will write a function to simulate the impact of Pele's arrival on American soccer. The function should take in a list of tuples, representing the number of tickets sold for each game in a season before and after Pele's arrival. The function should return the percentage increase in ticket sales for the season after Pele's arrival.

```python
def pele_impact(ticket_sales):
    # Calculate total ticket sales before and after Pele's arrival
    before_sales = sum([x[0] for x in ticket_sales])
    after_sales = sum([x[1] for x in ticket_sales])
    
    # Calculate percentage increase in ticket sales
    percentage_increase = (after_sales - before_sales)/before_sales * 100
    
    return percentage_increase
```

And there you have it, folks - the code that made Pele a success at the New York Cosmos! Keep practicing these exercises to hone your skills and become a champion like Pele.
In this chapter, we explored the code that made Pele successful during his time at the New York Cosmos. We provided some exercises to explore the physical conditioning and endurance that made Pele perform at his best, the Pele-Beckenbauer connection that resulted in a string of successful seasons for the New York Cosmos, and the impact that Pele's arrival made on American soccer.

In exercise 1, we wrote a `burn_calories` function to simulate Pele's conditioning and endurance routine. The function takes in a duration (in minutes) and returns the number of calories burned performing cardio exercises for that duration. The function multiplies the duration by a constant calorie burn rate per minute to calculate the total number of calories burned, and then returns that number.

In exercise 2, we wrote a `pele_beckenbauer_connection` function to simulate the Pele-Beckenbauer connection. The function takes in two lists representing the passes made by Pele and Beckenbauer respectively, and returns the number of successful passes completed between the two players. The function iterates over both lists, checking if the passes match and are successful, then increments the count for each successful pass.

In exercise 3, we wrote a `pele_impact` function to simulate the impact of Pele's arrival on American soccer. The function takes in a list of tuples representing the number of tickets sold for each game in a season before and after Pele's arrival, and returns the percentage increase in ticket sales for the season after Pele's arrival. The function first calculates the total ticket sales before and after Pele's arrival, then uses those numbers to calculate the percentage increase in ticket sales.

By practicing these exercises, one can get an idea of how Pele's success at the New York Cosmos was a result of his physical conditioning, his on-field rapport with Beckenbauer, and the impact he had on American soccer.


[Next Chapter](12_Chapter12.md)