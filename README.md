# eureka-ops
A simple, safe, sane operations guide for boring releases

1. Don't release on Monday or Friday
   Never release on day where you or your clients may have to work out of standard hours. [Patch Tuesday][https://en.wikipedia.org/wiki/Patch_Tuesday] exists for a reason, 
   As an additional - "Monday" means the first day of the work week, and "Friday" means the last day of the work week. So a public holiday on Monday means no release before Wednesday.

2. All code is reviewed by at least one person

3. Releases should be reviewed by zero people or at least two people.
   One person is prone to mistakes

4. Verbalise all commands
   Say the following out loud - "I am about to delete our production servers". That should fill you with dread, or worry any eavesdropping co-workers around you.
   [Pointing-and-calling][https://en.wikipedia.org/wiki/Pointing_and_calling] actions before taking them is shown to reduce errors by 85%, because your hand, eyes, mouth and ears are all in action.
   Having those commands heard by another operator even further reduces the risk that mistakes are made.
