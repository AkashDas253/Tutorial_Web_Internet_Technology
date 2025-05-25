## **Advanced Topics in Web Technology (5 Hours)**

---

### **1. Internet Telephony (1L)**

#### **Introduction**

* Internet Telephony refers to transmitting voice and multimedia over the Internet.
* Also known as **Voice over IP (VoIP)**.
* Replaces traditional PSTN (Public Switched Telephone Network).

#### **Voice over IP (VoIP)**

* **Functionality**:

  * Converts voice into digital packets.
  * Sends over IP networks.
* **Protocols used**:

  * SIP (Session Initiation Protocol) – call setup and teardown.
  * H.323 – older standard for multimedia communication.
  * RTP – transports audio/video.
* **Advantages**:

  * Cost-effective.
  * Integration with video and text.
* **Challenges**:

  * Latency, Jitter, Packet Loss.
  * Requires QoS mechanisms.

---

### **2. Multimedia Applications (2L)**

#### **Multimedia over IP**

* Delivering audio, video, and animations via IP networks.

##### **RSVP (Resource Reservation Protocol)**

* Reserves bandwidth for multimedia flows.
* Ensures QoS by negotiating resource requirements.

##### **RTP (Real-Time Transport Protocol)**

* Used for delivering audio and video over IP.
* Adds time-stamping and sequence numbers for synchronization.

##### **RTCP (RTP Control Protocol)**

* Works alongside RTP.
* Provides control information and feedback (e.g., packet loss).

##### **RTSP (Real-Time Streaming Protocol)**

* Controls streaming media servers (like a remote control).
* Allows pause, play, fast-forward in real time.

#### **Streaming Media**

* Real-time delivery of media content.
* Types:

  * Live Streaming
  * On-Demand Streaming
* Protocols: HTTP Live Streaming (HLS), MPEG-DASH.

#### **Codecs and Plugins**

* **Codec**: Compressor-Decompressor for audio/video.

  * Examples: MP3, H.264, VP9, Opus.
* **Plugins**: Extend browser capabilities to handle specific media.

  * Examples: Flash (deprecated), QuickTime, Silverlight.

#### **IPTV (Internet Protocol Television)**

* Delivers television content over IP.
* **Types**:

  * Live TV
  * Time-shifted TV
  * VOD (Video on Demand)
* Uses multicast, unicast, and adaptive streaming.

---

### **3. Search Engines and Web Crawlers (2L)**

#### **Definition**

* A **search engine** indexes the web to enable information retrieval.
* Examples: Google, Bing, DuckDuckGo.

#### **Metadata**

* Descriptive information about data.
* HTML tags: `<meta name="description">`, `<meta name="keywords">`.
* Helps search engines understand page content.

#### **Web Crawler**

* Also called spiders or bots.
* Automatically browses the web to collect pages.
* Follows hyperlinks, reads page content, sends data to the indexer.

#### **Indexing**

* Process of storing and organizing crawled data.
* Uses inverted index structure.
* Speeds up retrieval of relevant results.

#### **PageRank**

* Algorithm used by Google to rank pages.
* Pages are ranked based on:

  * Number and quality of incoming links.
  * Link importance distribution.

#### **Overview of SEO (Search Engine Optimization)**

* Techniques to improve page visibility in search engines.
* On-page SEO:

  * Use of metadata, keywords, headings, URLs, alt text.
* Off-page SEO:

  * Backlinks, domain authority.
* Technical SEO:

  * Site speed, mobile-friendliness, structured data.

---

## **Summary Table**

| Section                       | Topics                                                             |
| ----------------------------- | ------------------------------------------------------------------ |
| **Internet Telephony**        | VoIP, SIP, RTP, Challenges                                         |
| **Multimedia Applications**   | RSVP, RTP, RTCP, RTSP, Streaming Media, Codecs, Plugins, IPTV      |
| **Search Engines & Crawlers** | Metadata, Web Crawling, Indexing, PageRank, SEO (on-page/off-page) |

---
