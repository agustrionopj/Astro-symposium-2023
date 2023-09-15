---
title:
subtitle:
# widget: blank
# headless: true
weight: 20
active: true
design:
  columns: '1'
css_style: 
---
<h1 style="text-align: center; margin-bottom: 3rem;">Important Dates</h1>
<h3 style="text-align: center; margin-bottom: 1rem;">Countdown to late registration deadline</h3>
<div class="row justify-content-center">
        <div id="countdown">
                <div class="countdown-item">
                        <span class="countdown-value" id="days"></span>
                        <span class="countdown-label">Days</span>
                </div>
                <div class="countdown-item">
                        <span class="countdown-value" id="hours"></span>
                        <span class="countdown-label">Hours</span>
                </div>
                <div class="countdown-item">
                        <span class="countdown-value" id="minutes"></span>
                        <span class="countdown-label">Minutes</span>
                </div>
                <div class="countdown-item">
                        <span class="countdown-value" id="seconds"></span>
                        <span class="countdown-label">Seconds</span>
                </div>
        </div>
</div>

<div class="row" style="margin-bottom:2rem;">
        <!-- <div class="col-sm mt-3">
                <div class="card py-0">
                        <h4 class="card-header text-center text-white">
                                19 Jun 2023
                        </h4>
                        <div class="card-body">
                                <p class="card-title" style="font-size: 0.95rem;">
                                Launch of website and symposium flyer to public
                                </p>
                        </div>
                </div>
        </div> -->
        <div class="col-sm mt-3">
                <div class="card">
                        <h4 class="card-header text-center text-white" style="background-color: #D3D3D3;">
                                26 Jun 2023
                        </h4>
                                <div class="card-body" style="font-size: 0.95rem;">
                                        <!-- <p class="card-title" style="font-size: 0.95rem;"> -->
                                        <ul>
                                         <li class="text-muted">Open for registration and abstract submission</li>
                                        </ul>
                                                <!-- <ul style="padding-left:inherit;margin-left:.7rem;">
                                                        <li>Registration</li>
                                                        <li>Abstract submission</li>
                                                        <li>Invitation letters for participants</li>
                                                </ul> -->
                                        </p>
                                </div>
                </div>
        </div>
        <div class="col-sm mt-3">
                <div class="card">
                        <h4 class="card-header text-center text-white" style="background-color: #D3D3D3;">
                                11 Sep 2023
                        </h4>
                                <div class="card-body" style="font-size: 0.95rem;">
                                <ul>
                                        <li class="text-muted">Deadline for registration, abstract submission, and early bird registration fee payment</li>
                                </ul>
                                        <!-- <p class="card-title">
                                                <ul style="padding-left:inherit;margin-left:.7rem;">
                                                        <li>Program finalized</li>
                                                </ul>
                                        </p> -->
                                </div>
                </div>
        </div>
        <div class="col-sm mt-3">
                <div class="card">
                        <h4 class="card-header text-center text-white">
                                15 Sep 2023
                        </h4>
                                <div class="card-body" style="font-size: 0.95rem;">
                                        <!-- <p class="card-title" style="font-size: 0.95rem;"> -->
                                        <ul>
                                                <li>Symposium programme finalised</li>
                                                <li>Deadline for late registration
                                        </ul>
                                        </p>
                                </div>
                </div>
        </div>
        <div class="col-sm mt-3">
                <div class="card">
                        <h4 class="card-header text-center text-white">
                                30 Oct 2023
                        </h4>
                                <div class="card-body" style="font-size: 0.95rem;">
                                        <!-- <p class="card-title" style="font-size: 0.95rem;"> -->
                                        <ul>
                                                <li>Deadline for paper submission</li>
                                        </ul>
                                        </p>
                                </div>
                </div>
        </div>
</div>

<script>
const countdown = document.getElementById('countdown');
const daysEl = document.getElementById('days');
const hoursEl = document.getElementById('hours');
const minutesEl = document.getElementById('minutes');
const secondsEl = document.getElementById('seconds');

function updateCountdown(){
    const currentDate = new Date();
    const DeadlineDate = new Date("Sep 15, 2023 23:59:59").getTime();
//     const DeadlineDate = new Date("Sep 12, 2023 14:04:10").getTime();
    const timeRemaining = DeadlineDate - currentDate;

    if (timeRemaining <= 0) {
        clearInterval(timer);
    } else {
        const days = Math.floor(timeRemaining / (1000*60*60*24));
        const hours =Math.floor((timeRemaining % (1000*60*60*24))/(1000*60*60));
        const minutes = Math.floor((timeRemaining % (1000*60*60))/(1000*60));
        const seconds = Math.floor((timeRemaining % (1000*60))/1000);

        daysEl.innerHTML = days;
        hoursEl.innerHTML = hours;
        minutesEl.innerHTML = minutes;
        secondsEl.innerHTML = seconds;
    }
}

updateCountdown();
const timer = setInterval(updateCountdown, 1000);
</script>