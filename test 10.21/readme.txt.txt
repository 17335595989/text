10.21�ղ���

��������˧

1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:
		<script type="text/javascript">
			var a = '111';
			var b = '222';
			var c = a.concat(b);
            h1.innerHTML = (c);
		</script>
2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:
        <script>
             var str = '87';
             var estr = str.padEnd(6,'0');
             document.getElementById('h2').innerHTML= estr;
        </script>
3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:
	    <script type="text/javascript">
			var num = new Number(79387.348);
			document.getElementById('h3').innerHTML = num.toFixed(2);
		</script>
4.һ��ͼƬ��һ�����·��img/head/,icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:
<script type="text/javascript">
			var h4 = document.getElementById('h4');
			var img = 'img/head/icon/1.jpg';
			h4.innerHTML = img.substr(-5,5);
		</script>
5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh4��Ԫ����
��:
	<script type="text/javascript">
			var nstr = prompt('������֤��');
            var h4 = document.getElementById('h4');
            h4.innerHTML = nstr.toLocaleUpperCase();
		</script>
