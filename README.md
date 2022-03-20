# c-primer-plus
c字典的答案
是char g = 'a oi';
	int snum = 0, nnum = 0, onum = 0;
	//while (g != '#')
	{
		//scanf_s("%c", &g);
		if (g != '\n' && g != ' ')
			//{
			onum++;
		printf("onum=%d\n", onum);
	}
	if (g == '\n')
	{
		nnum++;
		printf("nnum=%d\n", nnum);
	}
	if (g == ' ')
	{
		snum++;
		printf("snum=%d\n", snum);
	}
