# shopee_code_2021_mcc

Determine how many contacts each user has had across the various tickets.
Two columns required:

● ticket_id
● ticket_trace/contact

○ Format: tickets in ascending order, total contact
  
For each ticket, identify all other ticket_ids that belong to the same user, sorted in ascending
order, as well as the total contacts the user had. If two tickets belong to the same user, the
value for uid/contact for both tickets should be identical.

ticket_id ticket_trace/contact
0 0-1-34567-78999, 14
1 0-1-34567-78999, 14
2 2-2456-4323-5343-6789, 13

Your submission should have 500,000 rows (excluding headers), each with 2 columns.
