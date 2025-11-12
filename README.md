# API-Performance-Project

## Description
This project focuses on **API functional and performance testing** using **Postman** and **Apache JMeter**.  
It includes manual and automated test cases, performance analysis under load, and professional reporting.  
The goal is to evaluate the **stability, speed, and reliability** of public APIs under different user loads.

---

## Tools and Technologies
| Tool | Purpose |
|------|----------|
| **Postman** | Functional API testing (GET, POST methods) |
| **Apache JMeter 5.6.3** | Load and performance testing |
| **Excel (Test Case Table)** | Documentation of test scenarios and results |
| **Git & GitHub** | Version control and collaboration |

---

## APIs Tested
| Method | Endpoint | Description |
|--------|-----------|-------------|
| **GET** | `https://reqres.in/api/users/2` | Retrieve user data |
| **POST** | `https://jsonplaceholder.typicode.com/users` | Create a new user |

---

## Performance Testing Setup
| Parameter | 1 User | 10 Users |
|------------|---------|----------|
| Number of Threads | 1 | 10 |
| Ramp-Up Period (sec) | 1 | 10 |
| Loop Count | 1 | 1 |

---

## Test Results Summary
| Users | Avg. Response Time (ms) | Error % | Throughput (req/s) |
|--------|--------------------------|----------|--------------------|
| 1 | 234 | 2.08% | 4.2 |
| 10 | 237 | 2.27% | 5.0 |

---

## Conclusions
- The **API remains stable** under increased load (1 → 10 users).  
- Average response time remains nearly constant, indicating **good scalability**.  
- Error rate is low, and throughput increased — confirming **efficient parallel request handling**.  
- The system can **handle concurrent users effectively** without performance degradation.

---

