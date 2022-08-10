This page demonstrates how a manager could manage the performance review process using Silver Bullet.

Run {[Template: Instantiate Page]} and select “Performance Review”

The [[template/page/Performance Review]] template is used to instantiate new performance reviews. The sections below can be used to help in tracking progress.

## Tasks
<!-- #query task where page =~ /🧑.+\/Review/ render "template/task" -->
* [ ] [[🧑 Mary/Reviews/2022-01@78]] Collect peer feedback  
* [ ] [[🧑 Mary/Reviews/2022-01@106]] Write performance review  
* [ ] [[🧑 Mary/Reviews/2022-01@137]] Deliver performance review  
* [x] [[🧑 John/Reviews/2022-01@79]] Collect peer feedback  
* [x] [[🧑 John/Reviews/2022-01@107]] Write performance review  
* [x] [[🧑 John/Reviews/2022-01@138]] Deliver performance review
<!-- /query -->

## In Progress
<!-- #query page where name =~ /🧑.+\/Review/ and status != "Done" render "template/performance-review" -->
* [[🧑 Mary/Reviews/2022-01]] (To Do) — rating: **TBD**
<!-- /query -->

## Completed
<!-- #query page where name =~ /🧑.+\/Review/ and status = "Done" render "template/performance-review" -->
* [[🧑 John/Reviews/2022-01]] (Done) — rating: **Ahead**
<!-- /query -->
