# binary-search
//lowe_bound
// lower bound, return the first index that is equal ot larger than target
int lower_bound(int target, vector<int> array){
  Int l = 0;
  Int r = array.size();
  while(l < r){  
    Int m = l + (r - l) / 2;
    if(array[m] < target){
       l = m + 1;
    }else{
       R = m;
    } 
   } 
  return l;
}


