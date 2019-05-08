# Specific Event Trigger For Event-Based Formulas
**Problem this solves:**
* How do you know which specific event triggered a formula?

**Solution**
Each event triggered formula will have access to all the events just under {{trigger}} but the specific event that triggered this execution can be found under {{trigger.event}}.

Using {{trigger.event}} will isolate the individual event that triggered the formula. Then you can use the objectId, contained in the event to retrieve the object from the associated element API. 