<style>
  @import url(//fonts.googleapis.com/css?family=Open+Sans);

  h2 {
    margin-bottom: 30px;
    color: #4679bd;
    font-weight: 400;
    text-align: center;
  }

  /* -----------------------------------------------
 * Timeline
 * --------------------------------------------- */
  .timeline {
    list-style: none;
    padding: 10px 0;
    position: relative;
    font-weight: 300;
  }
  .timeline:before {
    top: 0;
    bottom: 0;
    position: absolute;
    content: " ";
    width: 2px;
    background: #ffffff;
    left: 50%;
    margin-left: -1.5px;
  }
  .timeline > li {
    margin-bottom: 20px;
    position: relative;
    width: 50%;
    float: left;
    clear: left;
  }
  .timeline > li:before,
  .timeline > li:after {
    content: " ";
    display: table;
  }
  .timeline > li:after {
    clear: both;
  }
  .timeline > li:before,
  .timeline > li:after {
    content: " ";
    display: table;
  }
  .timeline > li:after {
    clear: both;
  }
  .timeline > li > .timeline-panel {
    width: calc(100% - 25px);
    width: -moz-calc(100% - 25px);
    width: -webkit-calc(100% - 25px);
    float: left;
    border: 1px solid #dcdcdc;
    background: #ffffff;
    position: relative;
  }
  .timeline > li > .timeline-panel:before {
    position: absolute;
    top: 26px;
    right: -15px;
    display: inline-block;
    border-top: 15px solid transparent;
    border-left: 15px solid #dcdcdc;
    border-right: 0 solid #dcdcdc;
    border-bottom: 15px solid transparent;
    content: " ";
  }
  .timeline > li > .timeline-panel:after {
    position: absolute;
    top: 27px;
    right: -14px;
    display: inline-block;
    border-top: 14px solid transparent;
    border-left: 14px solid #ffffff;
    border-right: 0 solid #ffffff;
    border-bottom: 14px solid transparent;
    content: " ";
  }
  .timeline > li > .timeline-badge {
    color: #ffffff;
    width: 24px;
    height: 24px;
    line-height: 50px;
    text-align: center;
    position: absolute;
    top: 16px;
    right: -12px;
    z-index: 100;
  }
  .timeline > li.timeline-inverted > .timeline-panel {
    float: right;
  }
  .timeline > li.timeline-inverted > .timeline-panel:before {
    border-left-width: 0;
    border-right-width: 15px;
    left: -15px;
    right: auto;
  }
  .timeline > li.timeline-inverted > .timeline-panel:after {
    border-left-width: 0;
    border-right-width: 14px;
    left: -14px;
    right: auto;
  }
  .timeline-badge > a {
    color: #ffffff !important;
  }
  .timeline-badge a:hover {
    color: #dcdcdc !important;
  }
  .timeline-heading h4 {
    font-weight: 400;
    padding: 0 15px;
    color: #4679bd;
  }
  .timeline-body > p {
    padding: 10px 15px;
    margin-bottom: 0;
  }
  .timeline-footer {
    padding: 5px 15px;
    background-color: #f4f4f4;
  }
  .timeline-footer p {
    margin-bottom: 0;
  }
  .timeline > li.timeline-inverted {
    float: right;
    clear: right;
  }
  .timeline > li:nth-child(2) {
    margin-top: 60px;
  }
  .timeline > li.timeline-inverted > .timeline-badge {
    left: -12px;
  }
  .no-float {
    float: none !important;
  }
  @media (max-width: 767px) {
    ul.timeline:before {
      left: 40px;
    }
    ul.timeline > li {
      margin-bottom: 0px;
      position: relative;
      width: 100%;
      float: left;
      clear: left;
    }
    ul.timeline > li > .timeline-panel {
      width: calc(100% - 65px);
      width: -moz-calc(100% - 65px);
      width: -webkit-calc(100% - 65px);
    }
    ul.timeline > li > .timeline-badge {
      left: 28px;
      margin-left: 0;
      top: 16px;
    }
    ul.timeline > li > .timeline-panel {
      float: right;
    }
    ul.timeline > li > .timeline-panel:before {
      border-left-width: 0;
      border-right-width: 15px;
      left: -15px;
      right: auto;
    }
    ul.timeline > li > .timeline-panel:after {
      border-left-width: 0;
      border-right-width: 14px;
      left: -14px;
      right: auto;
    }
    .timeline > li.timeline-inverted {
      float: left;
      clear: left;
      margin-top: 30px;
      margin-bottom: 30px;
    }
    .timeline > li.timeline-inverted > .timeline-badge {
      left: 28px;
    }
  }
</style>

<ul class="timeline">
  <li>
    <div class="timeline-badge"><a><i class="fa fa-circle" id="" /></a></div>
    <div class="timeline-panel">
      <div class="timeline-heading">
        <h4>Gunadarma University</h4>
      </div>
      <div class="timeline-body">
        <p>
          I have studied at Gunadarma University with a major in information
          systems. My GPA is 3.60 of 4.00.
        </p>
      </div>
      <div class="timeline-footer">
        <p class="text-right">2013 - 2017</p>
      </div>
    </div>
  </li>

  <li class="timeline-inverted">
    <div class="timeline-badge">
      <a><i class="fa fa-circle invert" id="" /></a>
    </div>
    <div class="timeline-panel">
      <div class="timeline-heading">
        <h4>PT. Duta Mitra - Nokia</h4>
      </div>
      <div class="timeline-body">
        <p>
          When I was in college, I also worked as a Junior Programmer at PT.
          Duta Mitra for web development projects on Nokia. In this project I am
          using the Codeigniter framework version 3, which includes PHP and
          jQuery.
        </p>
      </div>
      <div class="timeline-footer">
        <p class="text-right">2016 - 2017</p>
      </div>
    </div>
  </li>

  <li>
    <div class="timeline-badge"><a><i class="fa fa-circle" id="" /></a></div>
    <div class="timeline-panel">
      <div class="timeline-heading">
        <h4>
          PSMA (Pengembangan Sistem Manajemen Akademik) - Gundarma University
        </h4>
      </div>
      <div class="timeline-body">
        <p>
          Six months before I graduated, I worked at PSMA (Pengembangan Sistem
          Manajemen Akademik) - Gundarma University as a part timer. There I
          worked as helping student services in the academic and financial
          fields.
        </p>
      </div>
      <div class="timeline-footer">
        <p class="text-right">2017</p>
      </div>
    </div>
  </li>

  <li class="timeline-inverted">
    <div class="timeline-badge">
      <a><i class="fa fa-circle invert" id="" /></a>
    </div>
    <div class="timeline-panel">
      <div class="timeline-heading">
        <h4>PT. Trees Solutions</h4>
      </div>
      <div class="timeline-body">
        <p>
          After I graduated, I immediately got the opportunity to work at PT.
          Trees Solution as Technical Consultant - Frontend. Here I work as a
          team to build a website using React for Frontend and Python - Djanggo
          for Backend.
        </p>
      </div>
      <div class="timeline-footer">
        <p class="text-right">Nov 2017 - Present</p>
      </div>
    </div>
  </li>

  <li>
    <div class="timeline-badge"><a><i class="fa fa-circle" id="" /></a></div>
    <div class="timeline-panel">
      <div class="timeline-heading">
        <h4>Sidejob - Freelancer</h4>
      </div>
      <div class="timeline-body">
        <p>
          I'm trying to build my reputation in the field of web development. I
          open a wedding invitation web service and company profile.
        </p>
      </div>
      <div class="timeline-footer">
        <p class="text-right">2020 - present</p>
      </div>
    </div>
  </li>
  <li class="clearfix no-float" />
</ul>
