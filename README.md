# The challenge - Monkey Problem

We want to know if African monkeys can be taught about deadlocks. We locate a deep canyon and
fasten a rope across it, so the monkeys can cross hand-over-hand from one side to the other.

Passage along the rope follows these rules:

- Several monkeys can cross at the same time, provided that they are all going in the same
direction.
- If eastward moving and westward moving monkeys ever get onto the rope at the same time, a
deadlock will result (the monkeys will get stuck in the middle) because it is impossible for one
monkey to climb over another one while suspended over the canyon. It is also impossible for
monkeys to turn back.
- If a monkey wants to cross the canyon, he must check to see that no other monkey is currently
crossing in the opposite direction.
- Your solution should avoid starvation. When a monkey that wants to cross to the east arrives at
the rope and finds monkeys crossing to the west, the monkey waits until the rope in empty, but
no more westward moving monkeys are allowed to start until at least one monkey has crossed
the other way.

For this exercise, you are to write a program to simulate activity for this canyon crossing problem:

- Simulate each monkey as a separate process.
- Altogether, a lot of monkeys, whatever you want, will cross the canyon, with a random number
generator specifying whether they are eastward moving or westward moving.
- Use a random number generator, so the time between monkey arrivals is between 1 and 8
seconds.
- Each monkey takes 1 second to get on the rope. (That is, the minimum inter-monkey spacing is
1 second.)
- All monkeys travel at the same speed. Each traversal takes exactly 4 seconds, after the monkey
is on the rope.

# Details

The solution will be uploaded to a private git repository. We will need access to it in order to
review your code. Take all the time you need. We understand everyone’s time is limited.

# Advice

- Try to design and implement your solution as you would do for real production code. Build something we’d want to contribute to.
- The challenge is kind of open in scope. This is on purpose.
- Work on the git repo as you would do in a real situation.
- Documentation and maintainability is a plus.
- Good tests make the code easier to work on safely. It also is easier for us to review well-tested code :)
- Feel free to ask questions.


Enjoy it!
