This page demonstrates how a manager could manage the performance review process using Silver Bullet.

Run {[Template: Instantiate Page]} and select “Performance Review”

The [[template/page/Performance Review]] template is used to instantiate new performance reviews. The sections below can be used to help in tracking progress.

## Tasks
<!-- #query task where page =~ /🧑.+\/Review/ render "template/task" -->
* [ ] [[🧑 Mary/Reviews/2022-01@102]] Write performance review  
* [x] [[🧑 John/Reviews/2022-01@104]] Write performance review  
* [ ] [[🧑 Mary/Reviews/2022-01@133]] Deliver performance review  
* [x] [[🧑 John/Reviews/2022-01@135]] Deliver performance review  
* [ ] [[🧑 Mary/Reviews/2022-01@74]] Collect peer feedback  
* [x] [[🧑 John/Reviews/2022-01@76]] Collect peer feedback
<!-- /query -->

## In Progress
<!-- #query page where name =~ /🧑.+\/Review/ and status != "Done" render "template/performance-review" -->
* [[🧑 Mary/Reviews/2022-01]] (To Do) — rating: **TBD**
<!-- /query -->

## Completed
<!-- #query page where name =~ /🧑.+\/Review/ and status = "Done" render "template/performance-review" -->
* [[🧑 John/Reviews/2022-01]] (Done) — rating: **Ahead**
<!-- /query -->
