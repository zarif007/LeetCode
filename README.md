# LeetCode Patterns

2 pointers / sliding window

https://leetcode.com/discuss/study-guide/1688903/Solved-all-two-pointers-problems-in-100-days

Sub array => of condition (no more than 1/k freq of elms or sum of elm == target or Bitwise and == 0) or product less than k (check if k == 0 then return 0) 

Iterate until the condition breaks then iterate the first pointer and removing that elm until the condition satisfies 

Return max/min size of sub array or max value

Move to the right/left
https://leetcode.com/problems/separate-black-and-white-balls/description/

Subarray
https://leetcode.com/problems/count-complete-subarrays-in-an-array/
https://leetcode.com/problems/max-consecutive-ones-iii/description/

Min 
https://leetcode.com/problems/minimum-size-subarray-sum/

Found challenging (Work with extras)
https://leetcode.com/problems/replace-the-substring-for-balanced-string/

Moving left or right side (avoid medium like ‘_’ or ‘X’)
https://leetcode.com/problems/move-pieces-to-obtain-a-string/description/
https://leetcode.com/problems/swap-adjacent-in-lr-string/description/

Same pattern (Deleting Similar Ends/chars/elm)
https://leetcode.com/problems/minimum-length-of-string-after-deleting-similar-ends/description/
https://leetcode.com/problems/expressive-words/description/
https://leetcode.com/problems/longest-word-in-dictionary-through-deleting/description/
https://leetcode.com/problems/largest-merge-of-two-strings/

3Sum
https://leetcode.com/problems/valid-triangle-number/description/
https://leetcode.com/problems/3sum-closest/description/
https://leetcode.com/problems/3sum-with-multiplicity/description/
https://leetcode.com/problems/4sum/description/
https://leetcode.com/problems/3sum/description/
https://leetcode.com/problems/tuple-with-same-product/description/


BS
https://leetcode.com/problems/ways-to-split-array-into-three-subarrays/

Reverse
https://leetcode.com/problems/take-k-of-each-character-from-left-and-right/description/

Double Sum
https://leetcode.com/problems/continuous-subarray-sum/description/
https://leetcode.com/problems/longest-substring-with-at-least-k-repeating-characters/description/

Find decreasing/increasing
https://leetcode.com/problems/shortest-subarray-to-be-removed-to-make-array-sorted/description/

sliding window => subarray size of k 

Sometimes need to add string after that string to make n * 2 add operate sliding window
https://leetcode.com/problems/minimum-number-of-flips-to-make-the-binary-string-alternating/

Permutation / Anagram  in String/arr => take smaller one as the window size and check freq using map
https://leetcode.com/problems/group-anagrams/

Twice (solve(k) - solve(k - 1))
https://leetcode.com/problems/subarrays-with-k-different-integers/description/





Binary Search 
When the ans is in a big range (can be plot to a monotonically inc/dec graph) apply bs on the ans

Apply on ans (find min)
https://leetcode.com/problems/kth-smallest-number-in-multiplication-table/
https://leetcode.com/problems/split-array-largest-sum/description/
https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/description/
https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/description/
https://leetcode.com/problems/koko-eating-bananas/description/

Find Max
https://leetcode.com/problems/maximum-tastiness-of-candy-basket/description/


Total Log(n)
https://leetcode.com/problems/h-index-ii/description/

Paired vector (Max/elm till now, pref array)
https://leetcode.com/problems/find-right-interval/description/

Pref Sum
https://leetcode.com/problems/most-profit-assigning-work/description/
https://leetcode.com/problems/minimum-operations-to-make-all-array-elements-equal/description/
https://leetcode.com/problems/most-beautiful-item-for-each-query/



2D Vector (either start from x = n -1, y = 0 or x = 0, y = m - 1) 
https://leetcode.com/problems/search-a-2d-matrix-ii/description/

Search in Rotated sorted Array
https://leetcode.com/problems/search-in-rotated-sorted-array/description/
https://leetcode.com/problems/search-in-rotated-sorted-array-ii/description/

Peak element
https://leetcode.com/problems/peak-index-in-a-mountain-array/description/
https://leetcode.com/problems/find-peak-element/description/

Find an element (bound)
https://leetcode.com/problems/maximum-beauty-of-an-array-after-applying-operation/description/

Lower and Upper Bound
https://leetcode.com/problems/count-the-number-of-fair-pairs/
https://leetcode.com/problems/find-right-interval/
https://leetcode.com/problems/maximum-profit-in-job-scheduling/description/

Partition 
https://leetcode.com/problems/successful-pairs-of-spells-and-potions/description/
https://leetcode.com/problems/ways-to-split-array-into-three-subarrays/

Number Theory
https://leetcode.com/problems/minimize-the-maximum-of-two-arrays/description/


Greedy
Find the best (min or max)

Line Sweep
https://leetcode.com/problems/divide-intervals-into-minimum-number-of-groups/

Sort
https://leetcode.com/problems/the-number-of-weak-characters-in-the-game/description/


Allocation
https://leetcode.com/problems/task-scheduler/description/


Intervals
https://leetcode.com/problems/non-overlapping-intervals/description/

Stack
https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/

DP
https://leetcode.com/problems/jump-game-ii/description/



Stack
Find max or min from left or right

Find nearest min/max
https://leetcode.com/problems/steps-to-make-array-non-decreasing/submissions/1196960676/
https://leetcode.com/problems/check-if-word-is-valid-after-substitutions/description/

Deal with 3 elements 
https://leetcode.com/problems/132-pattern/

Both prev and next min/max
https://leetcode.com/problems/beautiful-towers-ii/description/
https://leetcode.com/problems/maximum-subarray-min-product/description/
https://leetcode.com/problems/apply-operations-to-maximize-score/description/

With condition
https://leetcode.com/problems/remove-duplicate-letters/description/
https://leetcode.com/problems/find-the-most-competitive-subsequence/

With sorting
https://leetcode.com/problems/car-fleet/description/

Min stack
https://leetcode.com/problems/maximum-width-ramp/description/


Partition
https://leetcode.com/problems/max-chunks-to-make-sorted-ii/submissions/1197515835/

Similar pattern (subarray count) 
Being the minimum (the num[i] is minimum)
https://leetcode.com/problems/maximum-subarray-min-product/description/
https://leetcode.com/problems/sum-of-subarray-ranges/description/

https://leetcode.com/problems/apply-operations-to-maximize-score/description/




