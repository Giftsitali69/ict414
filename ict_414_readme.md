README.md – WIRESHARK NETWORK ANALYSIS PRACTICAL (ICT414)

Rockview University

Department of Computer Science
Course Code:ICT414
Course Title: Information Security
Examination Type: Final Practical
Student: GIFT SITALI



1. Practical Overview

This practical required performing a basic network analysis using **Wireshark, focusing on capturing traffic generated when accessing:

[www.rocktv.app](http://www.rocktv.app)

The objective was to identify one HTTP GET request and its corresponding HTTP response, analyze packet details, and document the findings.



2. Steps Followed

. Launched Wireshark with administrator privileges.
. Selected the active network interface and started live capture.
. Visited the URL: http://www.rocktv.app in a web browser.
. Allowed the website to load and redirect automatically.
. Stopped the capture after enough packets were recorded.
. Applied the filter:
   ```
   http.host == "www.rocktv.app"
   ```
. Located the HTTP GET request and its server response.
. Took a screenshot showing filtered HTTP packets.
. Saved the capture file as ict414_capture.pcapng.
. Generated the final PDF report and README.



3. Required Analysis Results

Client (Source) IP Address:

10.0.2.15

Server (Destination) IP Address:

18.171.137.67

URL Requested:

http://www.rocktv.app

HTTP Response Code:

301 Moved Permanently

Request Status Explanation:

The request reached the server successfully. The server issued a 301 redirect, indicating that the resource has permanently moved—commonly to an HTTPS version of the site.



4. Screenshot

A screenshot showing the filtered HTTP GET request and its response is included as part of the submission.



5. Capture File Included

ict414_capture.pcapng



6. Repository Structure


ICT414-Wireshark-Practical
README.md
report_gift_sitali.pdf
ict414_capture.pcapng
screenshot.png



7. Submission Requirements Checklist

 Live capture performed using Wireshark
 HTTP GET request identified
 Correct source IP documented
 Correct destination IP documented
 Correct URL extracted
 Correct HTTP response code recorded
 Screenshot included
 Capture file saved as ict414_capture.pcapng
 README.md completed following exam structure
 PDF report generated



8. Bonus Analysis (Completed)

- Identification of HTTP method (GET).
- Observation of server behavior (301 permanent redirect).
- Note on security: HTTP is unencrypted, making all headers visible.



9. Conclusion**

The practical successfully demonstrates the ability to capture, filter, and analyze HTTP traffic using Wireshark. All required details including client server IPs, GET request, response code, and analysis were correctly identified. All submission materials have been prepared according to the ICT414 practical requirements.

