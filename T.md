# �ݸ屾

������Ϊ[l,r]
Ȼ�����и���λ��Ϊx,y������x<=y��

���������и�x�Ĺ���Ϊ:
	S_x=(Sum[x]-Sum[l-1])*(Sum[r]-Sum[x])+(Sum[y]-Sum[x])*(Sum[r]-Sum[y])
���������и�y�Ĺ���Ϊ:
	S_y=(Sum[y]-Sum[l-1])*(Sum[r]-Sum[y])+(Sum[x]-Sum[l-1])*(Sum[y-1]-Sum[x])
��A=Sum[x],B=Sum[y],C=Sum[l-1],D=Sum[r],E=Sum[y-1]
S_x=(A-C)*(D-A)+(B-A)*(D-B)
S_y=(B-C)*(D-B)+(A-C)*(E-A)

S_x-S_y=(A-C)*(D-E)+(D-B)*(C-A)
S_x-S_y=(A-C)*(B-E)
S_x-S_y=(sum[x]-sum[l-1])*(sum[y]-sum[y-1])

��Ȼʽ�ӱ�0��Ҳ����˵˳�������𰸲����С��