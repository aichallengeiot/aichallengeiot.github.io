The **3rd International Workshop on Challenges in Artificial Intelligence and Machine Learning for Internet of Things (AIChallengeIoT 2021)** will be held in conjunction with [ACM SenSys 2021](http://sensys.acm.org/2021/).


<script type="text/javascript">
function displayDate(dt) {
  var hour = dt.getHours();
  var minute = dt.getMinutes();
  var temp = '' + ((hour > 12) ? hour - 12 : hour);
  if (hour == 0)
    temp = '12';
  temp += ((minute < 10) ? ':0' : ':') + minute;
  temp += (hour >= 12) ? ' PM' : ' AM';
  temp += (dt.getDay() - dt.getUTCDay() == 1 ? ' (Nov. 17)' : '');
  return temp;
}

function getTimezoneOffset() {
  var offset = -(new Date()).getTimezoneOffset()/60;
  var temp = "UTC" + (offset >= 0 ? "+" : "") + offset;
  return temp;
}

function getLocalTimezone() {
  try {
    return Intl.DateTimeFormat().resolvedOptions().timeZone + ", " + getTimezoneOffset();
  }
  catch(e) {
    return getTimezoneOffset();
  }
}

function writeTimeRange(startTime, endTime) {
  var startTimeObj = new Date("2020-11-16T" + startTime + ":00.000+00:00");
  var endTimeObj = new Date("2020-11-16T" + endTime + ":00.000+00:00");

  return document.write(displayDate(startTimeObj) + " - " + displayDate(endTimeObj) + " (" + getLocalTimezone() +")");
}
</script>



#### Call for Papers

Artificial intelligence (AI) and machine learning (ML) are key enabling technologies for many Internet of Things (IoT) applications. However, the collection and processing of data for AI and ML is very challenging in the IoT domain. For example, there are usually a large number of low-powered sensors deployed in large geographical areas with possibly intermittent network connectivity. The sensors and their collected data may be owned by different users or organizations, which can bring further obstacles to data collection due to privacy concerns and noisy labels provided by different users. The successful application of AI/ML approaches in such scenarios with noisy and decentralized data is difficult. In addition, the amount of collected data that can be used for training AI/ML models is usually proportional to the number of users in the system, but the system may not be able to attract many users without a well-trained AI/ML model, and it is challenging to solve this dilemma.

This workshop focuses on how to address the above and other unique challenges of applying AI/ML in IoT systems. 

We invite researchers and practitioners to submit *papers describing original work, experiences, or vision* related to the entire lifecycle of an IoT system powered by AI and ML, including (but not limited to) the following topics:

- AI/ML in multi-agent, distributed, and decentralized settings
- AI/ML on low-powered and/or intermittently connected devices
- AI/ML with noisy and possibly adversarial data and labels
- Algorithms and techniques for evolving from a new system that is initially trained with only a small amount of data
- Algorithms and techniques for making use of data collected by geographically dispersed sensors to provide useful services through AI/ML
- Algorithms and techniques for reducing human effort in data labeling, including active learning
- Algorithms and techniques for sharing data and training AI/ML models while preserving user sensitive information, including federated learning
- Design and implementation of AI/ML-powered IoT systems
- Hardware, software, and tools for AI/ML in IoT
- IoT applications enabled by AI/ML
- Privacy and security of AI/ML in IoT

Submissions focusing on specific IoT applications and generic IoT systems are both welcome. We specifically encourage papers with forward-looking ideas that may initiate new research directions. We solicit the following types of submissions:

- **Regular papers** describing novel research work or experiences, up to 6 pages including figures and tables, but not including references (references can use additional pages as needed), which will be presented at the workshop as oral presentation
- **Vision/position papers** describing new research directions and challenges, up to 4 pages including figures, tables, and references, which will be presented at the workshop as a short oral presentation followed by interactive discussions

Submitted papers should be previously unpublished and not currently under review by another conference or journal. All accepted regular papers and vision/position papers will be published in the conference proceedings and the ACM Digital Library. 

All submissions should use the double column ACM proceedings format. The ACM template is available at: [https://www.acm.org/publications/proceedings-template](https://www.acm.org/publications/proceedings-template). LaTeX submissions should use the acmart.cls template (sigconf option), with the default 9-pt font. This format will be used also for the camera-ready version of accepted regular and vision/position papers. The submissions should include authors' names and affiliations (i.e., *not* be double-blind). Submissions will be reviewed by the program committee for novelty, relevance, and quality. At least one of the authors of every accepted paper/presentation must register and present the work at the workshop. Submissions should be in Adobe Portable Document Format (PDF).

The organizing committee will select a *best paper award* among submitted papers, which will be announced at the workshop.


#### Important Dates
- Abstract Registration: September 8, 2021 (11:59 pm anywhere on earth (UTC -12))
- Paper Submission: September 15, 2021 (11:59 pm anywhere on earth (UTC -12))
- Notification of Paper Acceptance: October 11, 2021


#### Workshop History

- [2020](https://aichallengeiot.github.io/2020/index.html)
- [2019](https://aichallengeiot.github.io/2019/index.html)



#### Organizing Committee

##### Program Chairs

- [Shuochao Yao](https://yscacaca.github.io/) (George Mason University, USA)
- [Bharathan Balaji](https://www.synergylabs.org/bharath/) (Amazon AI Lab, USA)


##### Steering Committee

- [Shiqiang Wang](https://researcher.watson.ibm.com/researcher/view.php?person=us-wangshiq) (IBM T. J. Watson Research Center, USA)
- [Jorge Ortiz](http://jorgeortizphd.info/) (Rutgers University, USA)
- [Mani Srivastava](https://www.ee.ucla.edu/mani-srivastava/) (University of California, Los Angeles, USA)



<script type="text/javascript">
var sc_project=8539485; 
var sc_invisible=1; 
var sc_security="2bff2be0"; 
var scJsHost = (("https:" == document.location.protocol) ? "https://secure." : "http://www.");
document.write("<sc"+"ript type='text/javascript' src='" + scJsHost + "statcounter.com/counter/counter.js'></"+"script>");
</script>

<noscript>
  <div class="statcounter"><a title="free web stats"
href="http://statcounter.com/" target="_blank"><img
class="statcounter"
src="https://c.statcounter.com/8539485/0/2bff2be0/1/"
alt="free web stats"></a></div>
</noscript>

