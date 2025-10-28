# S2.04.Mongo DB Queries

## Overview
This project showcases my work on querying a **collection of restaurants in USA**. The exercise involved importing a JSON database into MongoDB, experimenting with queries in **MongoDB Compass**, and then transferring them to a `.js` file in **IntelliJ IDEA**. The goal was to practice finding, projecting, filtering, and sorting data using MongoDB query methods and operators.

## Project Structure
- `restaurants.json`: Original dataset of NYC restaurants.  
- `restaurants.js`: Document containing all MongoDB queries, tested in Compass and executed in IntelliJ IDEA.  

## Skills Demonstrated
The queries cover multiple aspects of MongoDB operations:

### 1. **Finding Documents**
- Retrieve all restaurants.  
- Filter by borough, cuisine, and specific scores.  
- Query using ranges, logical operators, and regex for name patterns.

### 2. **Projecting Fields**
- Select specific fields (`restaurant_id`, `name`, `borough`, `cuisine`, `grades`).  
- Exclude `_id` when necessary.  
- Combine field projection with filtering.

### 3. **Sorting and Pagination**
- Sort by name, cuisine, or borough in ascending or descending order.  
- Limit results and skip documents to implement pagination.

### 4. **Filtering and Operators**
- Use comparison operators (`$gt`, `$lt`, `$ne`).  
- Use array queries for `grades` and coordinates.  
- Apply logical operators (`$and`, `$or`, `$not`) and modulus with `$mod`.  
- Work with dates (`ISODate`) in filtering grades by date.

### 5. **Advanced Queries**
- Combine multiple conditions without `$and`.  
- Filter by nested array elements (coordinates and grades).  
- Regex queries to match partial names at beginning, middle, or end.

## Achievement Levels
- **Level 1**: 17 correct queries  
- **Level 2**: 17–25 correct queries  
- **Level 3**: More than 25 correct queries ✅ (achieved in this project)

## Resources
- Original database: `restaurants.json`  
- Query testing: **MongoDB Compass**  
- Query implementation and submission: **IntelliJ IDEA** (`restaurants.js`)

This project demonstrates practical knowledge in MongoDB querying, including filtering, projection, sorting, array handling, and complex operators.
