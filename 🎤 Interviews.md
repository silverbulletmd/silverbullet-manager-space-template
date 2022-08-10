Run {[Template: Instantiate Page]} and select “Interview”

## Tasks
<!-- #query task where page =~ /🎤/ and done = false render "template/task" -->
* [ ] [[🎤 Fred@81]] Review CV and prepare specific questions  
* [ ] [[🎤 Fred@128]] Submit interview notes to ATS after interview
<!-- /query -->

## Upcoming
<!-- #query page where name =~ /🎤/ and date >= "{{today}}" select name, role order by date render "template/interview" -->
* [[🎤 Fred]] (Engineer)
<!-- /query -->

## Archive
<!-- #query page where name =~ /🎤/ and date < "{{today}}" order by date render "template/interview" -->

<!-- /query -->
