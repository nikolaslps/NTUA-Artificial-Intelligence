# Artificial Intelligence Projects (2023-24)

## Course Information
- **Course**: "Artificial Intelligence"
- **Academic Year**: 2023-24
- **Institution**: National Technical University of Athens (NTUA)
- **Department**: School of Electrical and Computer Engineering

## Laboratory Exercises

### Exercise 1: Pathfinding Algorithms in Mazes

#### Project Overview
This laboratory exercise focuses on implementing and analyzing pathfinding algorithms in N×N dimensional mazes. The goal is to explore various shortest-path algorithms and construct different cost functions for measuring actual distances and estimating distances to the target node (heuristics).

#### Key Objectives
- **Algorithm Implementation**: Develop various shortest-path finding algorithms and their variants
- **Cost Function Design**: Create functions for measuring actual distances and heuristic distance estimation
- **Parameter Experimentation**: Test different algorithm parameters to study their impact on complexity, execution time, and optimal path finding
- **Ghost Avoidance**: Navigate to the endpoint while avoiding a ghost that pursues using its own A* algorithm at each step

#### Technical Components
- Multiple pathfinding algorithms running on mazes of different sizes
- Comparative analysis based on algorithm complexity and optimal path finding capability
- Performance evaluation across different maze dimensions

#### Implementation Template
- `AL_24_EX1.ipynb`

### Exercise 2: Movie Recommendation System

#### Project Overview
This laboratory exercise involves building a comprehensive movie recommendation system that generates suggestions based on both movie characteristics and user ratings. The system integrates content-based filtering with collaborative filtering techniques.

#### Dataset Description
- **movies_metadata.csv**: Contains movie characteristics including genre, director, actors, keywords, etc. from IMDB
- **ratings.csv**: Real user ratings divided into training and test sets
- **Additional Files**: `db.pl`, `PrologIntro.ipynb`, `test_ratings.csv`, `train_ratings.csv`

#### Key Components

##### Prolog Rule Development
- Create simple Prolog rules to find movies with common themes, directors, etc.
- Implement queries for generating better recommendations
- Construct scalable queries that return movies with varying degrees of similarity

