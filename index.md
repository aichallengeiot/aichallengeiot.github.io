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
  
<br/>

**<u>Location:</u>** Convento de São Francisco: Room Aeminium - C1A2

**<u>Zoom link:</u>** [https://sensys-buildsys-21.dei.uc.pt/vc/room2](https://sensys-buildsys-21.dei.uc.pt/vc/room2)
 
**<u>Youtube channel:</u>** [https://sensys-buildsys-21.dei.uc.pt/yt/room2](https://sensys-buildsys-21.dei.uc.pt/yt/room2)
  
<br/>

<br/>

### Workshop Program (Wednesday, November 17, 2021)

<br/>

**NOTE: All times below are in Coordinated Universal Time (GMT). To convert to your local time zone, you may visit [here](https://time.is/compare/1000AM_17_Nov_2021_in_UTC)**.  
Some examples:  

- PST (U.S. Pacific) = UTC-8
- EST (U.S. Eastern) = UTC-5 
- GMT (Coimbra, Portugal) = UTC+0  
- CET (Central Europe) = UTC+1  
- IST (India) = UTC+5:30  
- CST (China) = UTC+8  
- JST (Japan) = UTC+9

**10:00 - 10:10 (GMT time zone): [Welcome & Opening Remarks]()**  
- [Shuochao Yao]() (Geroge Mason University, USA)
- [Bharathan Balaji]() (Amazon AI Lab, USA)

<br/>

***Technical Session 1***  

**10:10 - 10:30 (GMT time zone): [Better Never Than Late: Timely Edge Video Analytics Over the Air]()**  
*Vinod Nigade, Ramon Winder, Henri Bal (VU Amsterdam), Lin Wang (VU Amsterdam & TU Darmstadt)*

**10:30 - 10:50 (GMT time zone): [Characterising the Role of Pre-Processing Parameters in Audio-based Embedded Machine Learning]()**  
*Wiebke Toussaint (Delft University of Technology), Akhil Mathur (Nokia Bell Labs), Aaron Yi Ding (Delft University of Technology), Fahim Kawsar (Nokia Bell Labs)*

**10:50 - 11:10 (GMT time zone): [Vision Paper: Towards Software-Defined Video Analytics with Cross-Camera Collaboration]()**  
*Juheon Yi (Seoul National University), Chulhong Min, Fahim Kawsar (Nokia Bell Labs)*

<br/>

**11:10 - 11:30 (GMT time zone): Break**

<br/>


***Technical Session 2***

**11:30 - 11:50 (GMT time zone): [AI-assisted Cell-Level Fault Detection and Localization in Solar PV Electroluminescence Images]()**  
*Ahan M R, Akshay Nambi, Tanuja Ganu, Dhananjay Nahata, Shivkumar Kalyanaraman (Microsoft Research)*

**11:50 - 12:10 (GMT time zone): [Exploring Co-dependency of IoT Data Quality and Model Robustness in Precision Cattle Farming]()**  
*Franz Papst (TU Graz / CSH Vienna), Katharina Schodl (ZuchtData EDV-Dienstleistungen GmbH), Olga Saukh (TU Graz / CSH Vienna)*

**12:10 - 12:30 (GMT time zone): [OntoAugment: Ontology Matching through Weakly-Supervised Label Augmentation]()**  
*Fabio Maresca (University of Naples Federico II), Gürkan Solmaz (NEC Laboratories Europe), Flavio Cirillo (NEC Laboratories Europe)*

**12:30 - 12:50 (GMT time zone): [Through-Screen Visible Light Sensing Empowered by Embedded Deep Learning]()** 
*Hao Liu, Hanting Ye, Jie Yang, Qing Wang (Delft University of Technology)*


<br/>

**12:50 - 14:00 (GMT time zone): Break**

<br/>


***Technical Session 3***

**14:00 - 14:20 (GMT time zone): [Deep Contextualized Compressive Offloading for Images]()**
*Bo Chen (University of Illinois at Urbana-Champaign), Zhisheng Yan (George Mason University), Hongpeng Guo, Zhe Yang(University of Illinois at Urbana-Champaign), Ahmed Ali-Eldin (Chalmers University of Technology and UMass Amherst), Prashant Shenoy (University of Massachusetts Amherst), Klara Nahrstedt (University of Illinois at Urbana-Champaign)*

**14:20 - 14:40 (GMT time zone): [Federated Learning for Internet of Things]()** 
*Tuo Zhang, Chaoyang He, Tianhao Ma, Lei Gao, Mark Ma, Salman Avestimehr (University of Southern California)*

**14:40 - 15:00 (GMT time zone): [Device or User: Rethinking Federated Learning in Personal-Scale Multi-Device Environments]()**
*Hyunsung Cho (Carnegie Mellon University), Akhil Mathur, Fahim Kawsar (Nokia Bell Labs)*

**15:00 - 15:20 (GMT time zone): [Sensor Virtualization for Efficient Sharing of Mobile and Wearable Sensors]()** 
*Jian Xu (Stony Brook University), Arani Bhattacharya (IIIT-Delhi), Aruna Balasubramanian (Stony Brook University), Donald E. Porter (UNC Chapel Hill)*

**15:20 - 15:40 (GMT time zone): [Decentralized Federated Learning Framework for the Neighborhood: A Case Study on Residential Building Load Forecasting]()** 
*Jiechao Gao, Wenpeng Wang, Zetian Liu, Md Fazlay Rabbi Masum Billah, Brad Campbell (University of Virginia)*


<br/>

**15:40 - 15:50 (GMT time zone): Closing Remarks**

<br/>


#### Call for Papers

The call for papers is available [here](https://aichallengeiot.github.io/cfp.html)

#### Important Dates
- ~~Abstract Registration: September 8, 2021 (11:59 pm anywhere on earth (UTC -12))~~  New submissions are now allowed until the paper submission deadline
- Paper Submission: ~~September 15~~ FINAL deadline - **September 24, 2021** (11:59 pm anywhere on earth (UTC -12))
- Notification of Paper Acceptance: October 15, 2021


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


##### Program Committee
- [Achin Jain](https://jainachin.github.io/) (Amazon, USA)
- [Andreas Reinhardt](https://www.areinhardt.de/) (TU Clausthal, Germany)
- [Bo Wei](https://www.northumbria.ac.uk/about-us/our-staff/w/bo-wei/) (Northumbria University, UK)
- [Dezhi Hong](https://cseweb.ucsd.edu/~dehong/) (University of California, San Diego, USA)
- [Diana Popescu](https://www.kcl.ac.uk/people/diana-popescu) (Cambridge University, UK)
- [Francesco Fraternali](https://cseweb.ucsd.edu/~frfrater/) (University of California, San Diego, USA)
- [Le Viet Duc](https://people.utwente.nl/v.d.le) (University of Twente, Netherlands)
- [Liangzhen Lia](https://aichallengeiot.github.io) (Facebook, USA)
- [Manuel Roveri](http://roveri.faculty.polimi.it/) (Politecnico di Milano, Italy)
- [Qing Wang](https://www.st.ewi.tudelft.nl/qing/) (TU Delft, Netherlands)
- [Rui Tan](https://personal.ntu.edu.sg/tanrui/) (Nanyang Technological University, Singapore)
- [Salma Elmalaki](https://faculty.sites.uci.edu/elmalaki/) (UC Irvine, USA)
- [Shaohan Hu](https://hushaohan.github.io/) (JPMorgan Chase - Future Lab for Applied Research and Engineering, USA)
- [Sujan Kumar Gonugondla](https://www.linkedin.com/in/sujan-kumar-gonugondla-ab6787142) (Amazon, USA)
- [Swarnava Dey](https://aichallengeiot.github.io) (Tata Consultancy Services Ltd.)
- [Urmish Thakker](https://urmish.github.io/) (ARM, USA)


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

