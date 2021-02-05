## Steps ##

1. Space columns out evenly
2. Delete column with header "caller name"
3. Insert new column A - call date
4. Add call dates - I know data set started on May 4 and is continuous, so use time of call to determine dates
5. Delete row 78
6. Delete row 104
7. Delete row 139
8. Delete row 200
9. Delete column with header "caller email"
10. Find and replace ";" with ":"
11. Erase rows where Category of Question is not answered/obvious the call did not lead to a COVID test
12. Erase rows where Tier 2 action taken is blank
13. Fill in Country of origin for rows where it appears to be multiple people on one call
14. Change "Mexico (US Resident)" to "Mexico" in rows 80/81
15. Fill in"Caller county for rows where it appears to be multiple people on one call
16. Fill in Zip code for rows where it appears to be multiple people on one call
17. Delete column with header "phone number"
18. Delete column with header "family/home contact"
19. Delete column with header "Category of question"
20. Text to columns in column G to split adults and minors in household into separate columns
21. Replace "ads" "adult" "adults" "adultos" with blank space
22. Manually replace "ad" in adults column with blank space
23. Replace "kid" and "kids" with blank space in minors column
24. Delete column with Tier 2 referral name
