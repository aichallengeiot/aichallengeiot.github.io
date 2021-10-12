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

