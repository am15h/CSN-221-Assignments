# CSN-221-Assignments

**AMISH GARG 18114004**

    mov r1,1
    mov r2,0
    .loop1
    	mov r3,0
    	mov r4,0
    	.loop2
    		add r4 , r4 , 1
    		.loop3
    			mov r5 , r4
    			add r5 , r5 , 1
    			mov r6 , r4
    			mul r6 , r6 , r4
    			mul r6 , r6 , r4
    			mov r7 , r5
    			mul r7 , r7 , r5
    			mul r7 , r7 , r5
    			add r8 , r6 , r7
    			cmp r8 , r1
    			beq.method1
    				.method1
    				add r3 , 1
    				mov r9 , 1
    				add r9 , r9 , 1
    				cmp r9 , r5
    				bgt.loop3
    				cmp r9 , r4
    				bgt.loop2
    			
    cmp r3 , 2
    	beq.method2
    		.method2
    		mov r10 , r1
    		add r2 , 1
    
    add r1 , 1
    	cmp 1 , r2
    	bgt.loop1

Answer stored in **r10**
