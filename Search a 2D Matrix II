class Solution {
    public boolean searchMatrix(int[][] matrix, int target) {
        int n = matrix.length;
        int m = matrix[0].length;
        // for(int i=0;i<n;i++){
        //     for(int j=0;j<m;j++){
        //         if(matrix[i][j]==target) return true;
            
        //         else if(matrix[i][j]>target){
        //         break;
        //         }
        //     }
        // }
        // return false;

        int row =0;
        while(row<n){
            int s =0;
            int e =m-1;
            while(s<=e){
                // int mid = s+(e-s)/2;
                int mid =(s+e)/2;
                int v= matrix[row][mid];
                if(v==target) return true;
                else if(target>v){
                    s=mid+1;
                }
                else{
                    e=mid-1;
                }
            }
            row++;
        }
        return false;
    }
}
