int* twoSum(int* nums, int numsSize, int target, int* returnSize){
    int *resultado = (int*)malloc(2 * sizeof(int));
    
for(int i; i<numsSize; i++){
    for(int j = i+1; j<numsSize; j++){
        int resta = target - nums[i];
        
        if(resta == nums[j]){
            *returnSize = 2;
            resultado[0] = i;
            resultado[1] = j;
            return resultado;
        }
    }
}
    *returnSize = 0;
    free(resultado);
    return NULL;
}
