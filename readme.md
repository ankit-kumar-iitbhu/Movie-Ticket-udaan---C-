Input format

1. Adding screen:

add-screen <screen-name> <rows> <seats-per-row> <list-of-asley-seats-separeted-by-space>

2. Reserve Seats:

reserve-seat <screen-name> <row_number> <seats-number>

3. Get Vacant seats:

get-unreserved-seats <screen-name> <row_number>

4. Suggest seats based on user preference:

suggest-contiguous-seats <screen-name> <number-of-seats> <row_number> <choice-of-seat-number>

Output/Response format

1. "success"  ----->>>>If request is successfull
2. "failure"  ----->>>>If request fails
3. "none"     ----->>>>sometimes it none
