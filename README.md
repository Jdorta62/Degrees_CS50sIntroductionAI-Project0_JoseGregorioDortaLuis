# Degrees_CS50sIntroductionAI-Project0_JoseGregorioDortaLuis

## Objective
This project involves building a program that determines the "degrees of separation" between two actors by finding the shortest path that connects them through shared movies.

## Key Concepts
- **Search Problem**: States are actors, actions are movies.
- **Breadth-First Search**: The method used to find the shortest connection path.
- **Data**: Provided as CSV files for actors, movies, and the relationships between them.

## Steps
1. **Download** the [distribution code](https://cdn.cs50.net/ai/2023/x/projects/0/degrees.zip) and extract the data.
2. **CSV Files**:
   - `people.csv`: Includes actor IDs, names, and birth years.
   - `movies.csv`: Contains movie IDs, titles, and release years.
   - `stars.csv`: Maps actors to movies.
3. **Main Task**: Implement the `shortest_path` function in `degrees.py`, which returns the minimum connection between two actors.

## Implementation
- Complete the `shortest_path` function to return the shortest path from one actor to another.
- Use the `neighbors_for_person` function to find actors who have starred in the same movies.
- Optimize the search by checking for the goal when nodes are added to the search frontier.

## Hints
- Implement an efficient search algorithm by detecting the goal as early as possible.
- Use the provided `Node`, `StackFrontier`, and `QueueFrontier` structures from `util.py`.

## Testing
- Test the implementation with `check50` for correctness and `style50` for coding style.

## Submission
- Submit your code using `submit50 ai50/projects/2024/x/degrees` after following the setup instructions.

## Additional Resources
- Visit [CS50 AI 2024 Degrees Project](https://cs50.harvard.edu/ai/2024/projects/0/degrees/#degrees) for more details.

