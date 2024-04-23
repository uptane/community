## Principal decisions and topics from the Mar. 12, 2024 Uptane Standards committee meeting

* Meeting series will move permanently to a new Zoom series ([link](https://toradex.zoom.us/j/89160183478?pwd=Zk5qZ0pjcWErWFlwWk10ME5oWHFDUT09))

* Discussion on terminology changes in the Uptane standard: principally, some terms are auto-industry specific and not well-suited to the use of Uptane in other industries. "ECU" is particularly industry specific, and Uptane implementations outside of automotive (and within automotive) may not map each Uptane "ECU" to one physically distinct ECU anyway. Alternatives were discussed:
  * "Controller" suggested by Ira; used often in EE and radio
  * "Component" was discussed, but is a no-go because ISO/SAE 21434 and 24089 and 26262 have a definition of component that is at odds with this
  * "Embedded system" - could work, but is a bit overloaded
  * "USU" (Updateable software unit) suggested; rejected because it's too tied to concepts of unit testing
  * "Updateable component" - nice happy medium?
  * ECU is defined in 3.1.7 of 24089 as an "embedded device in a vehicle whose software (3.1.15(3.1.15)) can be updated"
