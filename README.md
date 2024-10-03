## Social Network Analysis Using Neo4j

### Introduction
Social networks are critical for understanding human interactions, relationships, and community behavior. With the increasing complexity of social interactions in digital platforms, it becomes essential to leverage graph databases for efficient data modeling and analysis. This project utilizes Neo4j to create a structured representation of social interactions, enabling various queries that uncover insights into user behavior and network structure.

### Nodes

1. **User**: Represents individuals in the network, characterized by attributes such as name.

2. **Post**: Represents content created by users, characterized by attributes like text and unique identifiers.

### Relationships

1. **FRIEND**: Represents a friendship connection between two users.

2. **POSTED**: Indicates that a user has created a post.

3. **COMMENTED**: Indicates that a user has commented on a post.

4. **LIKED**: Indicates that a user has liked a post.

### Recommendations
Using a friends-of-friends algorithm, we generated recommendations for potential new connections. This approach can enhance user engagement by facilitating new friendships, thus expanding the network.
