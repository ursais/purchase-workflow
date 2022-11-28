Inspired on OCA module sale_order_revision, this module was rebuilt to implement
purchase_order_revision.

On locked orders, you can click on New Revision. This
will create a new revision of the RFQ, with the same base number and a
'-revno' suffix appended. A message is added in the chatter saying that a new
revision was created.

In the form view, a new tab is added that lists the previous revisions, with
the date they were made obsolete and the user who performed the action.

The old revisions of a purchase order are flagged as inactive, so they don't
clutter up searches.
