/*無須刪減陣列內容，針對條件做置換，並對其數量(長度)計算即可*/
class Solution {
    public int removeElement(int[] nums, int val) {
/*     if(nums.length==0){
            return 0;
       }//先判斷陣列長度是否為0，若無陣列長度則節省時間
*/
       int index=0;//要輸出的答案，此值用來判斷陣列中有幾個不為val的值
       for(int i=0;i<nums.length;i++){
           if(nums[i]!=val){
                nums[index] = nums[i];  //判斷不為val值的才放到陣列前面，因此陣列後方超過長度(index值)的部分不重要
                index++;
            } 
    }
        return index;
    }
}
