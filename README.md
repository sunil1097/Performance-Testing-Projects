# 🚀 Performance Testing Projects (Apache JMeter)

This repository contains a collection of performance testing projects built using **Apache JMeter**. It covers both **API testing** and **web application load testing**, designed for beginners and QA professionals who want to practice real-world performance scenarios. Each project includes multiple test cases, structured test plans, and result analysis.

---

## 🧰 Tools & Technologies
- **Apache JMeter**
- **Postman** (for manual API validation)
- **CSV Data Files** (for parameterization)
- **GitHub** (version control)

---

## 📂 Projects Included

### ✅ 1. ReqRes API Performance Testing
- Public dummy API: [https://reqres.in](https://reqres.in)
- Methods tested: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`
- Focus: Basic API performance testing
- Metrics: Avg. response time, error %, throughput

### ✅ 2. BlazeDemo Web App Load Test
- Web App: [https://blazedemo.com](https://blazedemo.com)
- Simulated user actions: search flights, purchase ticket
- Focus: End-to-end web application load testing
- Thread configuration with ramp-up and loop count

### ✅ 3. GitHub API (Optional/Advanced)
- Authenticated API testing using Bearer Token
- POST: Create repo, GET: List repos, DELETE: Remove repo
- Added pre-request scripts & environment variables

---

## 📊 Metrics Tracked

- ✅ Response Time (Average, Min, Max)
- ✅ Throughput (requests/sec)
- ✅ Latency
- ✅ Error Percentage
- ✅ Number of active users

---

## 🧪 How to Run the Projects

1. Open Apache JMeter.
2. Load the `.jmx` test file of the project.
3. Configure Thread Group as needed:
   - Users
   - Ramp-Up Time
   - Loop Count
4. Run the test.
5. Analyze results using:
   - View Results Tree
   - Summary Report
   - Aggregate Graph
   - Graph Results

---

## 📁 Folder Structure

