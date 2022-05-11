### Trigers
* trigger **TriggerName** on **ObjectName** (**trigger_events**) 
  * triger _events:
    * before insert
    * before update
    * before delete
    * after insert
    * after update
    * after delete
    * after undelete<br>

* Trigger.new : 
  * Returns a list of the new versions of the sObject records. 
  * Note that this sObject list is only available in insert and update triggers, and the records can only be modified in before triggers.

 
* Trigger.old : 
  * Returns a list of the old versions of the sObject records. 
  * Note that this sObject list is only available in update and delete triggers.
