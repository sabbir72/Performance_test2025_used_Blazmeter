# 🚀 Load Test Summary – BlazeDemo Site

## 📄 Executive Summary  [🔗 Open PDF Report](https://drive.google.com/drive/u/1/folders/1D1vlYZscPv8Ne1qq2RJghCLBcZvTJcfu)

This document summarizes the results of a load test performed on May 12, 2025, using 50 virtual users over a duration of 9 minutes.

---

## 💡 Overall Verdict: GOOD

The system demonstrated a **healthy and stable performance** under medium traffic (50 Virtual Users). The load was handled efficiently without any errors or resource bottlenecks.

---

## 📌 Positive Indicators

| Metric                  | Result        | Benchmark             | Evaluation                    |
|-------------------------|---------------|------------------------|-------------------------------|
| **Avg. Response Time**  | 723 ms        | Ideal: < 1000 ms       | ✅ Good – Fast response        |
| **90% Response Time**   | 1787 ms       | Ideal: < 2000 ms       | ✅ Acceptable – Within limits |
| **Error Rate**          | 0%            | Ideal: < 1%            | ✅ Excellent – No failures     |
| **Throughput**          | 2.55 hits/sec | Depends on app logic   | ✅ Healthy flow                |
| **CPU/Memory Usage**    | < 75%         | Ideal: < 80%           | ✅ Stable under load           |

---

## ⚠️ Minor Considerations

- The **90th percentile response time (1787 ms)** is significantly higher than the average (723 ms), indicating that **some users may experience latency under load peaks**.
- While this is within acceptable limits, performance tuning could reduce these spikes.

---

## 🚀 What This Means

- The site is capable of handling **up to 50 concurrent users** with no noticeable degradation in performance.
- Response times are well within acceptable limits for standard user interactions.
- **No system or application errors** occurred during the test.

---

## 🟢 Conclusion

- ✅ **PASS** for small to mid-scale application usage.
- ✅ Suitable for **real-world moderate traffic**.
- 🔄 **Next Steps**:
  - Scale testing up to **100+ users**
  - Introduce **peak-hour simulation**
  - Monitor **longer-duration behavior**

---

## 🧪 Test Details

- **Test Name**: Blaz_Rec2025
- **Tool Used**: JMeter (executed via BlazeMeter)
- **Location**: West India (Mumbai, Azure)
- **Executed By**: Sabbir Ahamed
- **Test Duration**: 9 minutes (03:51 PM – 04:01 PM, May 12, 2025)

---

## 📘 Glossary

- **Throughput**: Requests handled per second.
- **Response Time**: Time from request initiation to complete response received.
- **Latency**: Time from request sent to first byte received.
- **90% Response Time**: Time within which 90% of all requests completed.
- **Error Rate**: Percentage of failed requests.

---

*Generated based on performance data from "Executive summary.pdf".*
