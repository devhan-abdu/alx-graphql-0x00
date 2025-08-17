# alx-graphql-0x00: Writing GraphQL Queries

This repository contains a series of exercises focused on writing fundamental GraphQL queries to retrieve data from a provided API. The primary objective is to understand how to fetch specific data points using fields and arguments in a GraphQL query.

## 0. Write a Query to Get a Specific Character by ID

### **Objective**

Learners will write a GraphQL query to retrieve a specific character's information using their ID.

### **Instructions**

1.  Write a GraphQL query using the `character(id: ID!)` field to fetch the details of a character.
2.  The query must include the following fields: `id`, `name`, `status`, `species`, `type`, `gender`.
3.  The exercises require you to create queries for character IDs **1, 2, 3, and 4**.

### **Repository Files**

This repository is structured to guide you through the tasks. The files are organized as follows:

* `README.md`: This file.
* `character-id-1.graphql`: Your GraphQL query for character ID 1.
* `character-id-1-output.json`: The expected JSON output from the query for character ID 1.
* `character-id-2.graphql`: Your GraphQL query for character ID 2.
* `character-id-2-output.json`: The expected JSON output from the query for character ID 2.
* `character-id-3.graphql`: Your GraphQL query for character ID 3.
* `character-id-3-output.json`: The expected JSON output from the query for character ID 3.
* `character-id-4.graphql`: Your GraphQL query for character ID 4.
* `character-id-4-output.json`: The expected JSON output from the query for character ID 4.

### **Example Query & Expected Output**

To help you get started, here is an example of the query you should write and the corresponding JSON output you would receive.

#### **`character-id-1.graphql`**
This file should contain a query similar to the following, which targets the character with ID `1`:

```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}