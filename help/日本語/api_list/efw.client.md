<a href="../api_list.md">�߂�</a>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="../../���{��/api_list/efw.client.md">���{��</a>
&nbsp;<a href="../../����/api_list/efw.client.md">����</a>
&nbsp;<a href="../../English/api_list/efw.client.md">English</a>
<H3>efw.client�̏ڍ�</H3>
<HR>


<H3><A NAME="fire">fire</A></H3>
<pre>
fire ( <A href="#efw.eventParams">eventParams</A> )</PRE>
<DL>
<DD>Ajax���Ăяo�����߂̓�����֐��B
 1���Ajax�̓p�����[�^�[�t�H�[�}�b�g���擾���A2���Ajax�����s����B
<P>
<DD><DL>
<B>�p�����[�^:</B>
<DD><CODE><A href="#efw.eventParams">eventParams</A></CODE> - �C�x���g�p�����[�^�[�A�K�{�B
</DL></DD>
<HR>

<H3><A NAME="pickup">pickup</A></H3>
<pre>
pickup ( <A href="#efw.event.paramsFormat">paramsFormat</A> , <A href="#efw.eventParams.manualParams">manualParams</A> )</PRE>
<DL>
<DD>�p�����[�^�l���擾����֐��B�ifire�֐��@�\�̈ꕔ���j

<P>
<DD><DL>
<DT><B>�߂�l:</B>
<DD><CODE><A href="#efw.event.fire.requestParams">requestParams</A></CODE> - ���N�G�X�g�p�����[�^�[�܂��͂��̊�ɏ]���f�[�^�B
</DL></DD>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.event.paramsFormat">paramsFormat</A></CODE> - �p�����[�^�[�t�H�[�}�b�g�A�K�{�B
<DD><CODE><A href="#efw.eventParams.manualParams">manualParams</A></CODE> - �蓮�p�����[�^�[ �A�I�v�V�����B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="show">show</A></H3>
<pre>
show ( <A href="#efw.event.fire.eventResult">eventResult</A> )</PRE>
<DL>
<DD>�l����ʂɕ\������֐��B�ifire�֐��@�\�̈ꕔ���j
<P>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.event.fire.eventResult">eventResult</A></CODE> - 2���Ajax�̎��s���ʂ܂��͂��̊�ɏ]���f�[�^�A�K�{�B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="alert">alert</A></H3>
<pre>
alert ( message , callback );                                                   //callback = function () { ... };
</PRE>
<DL>
<DD>Jquery UI��Alert���b�Z�[�W�{�b�N�X���Ăяo���֐��B
<P>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE>message</CODE> - �\�����郁�b�Z�[�W�A������A�K�{�B
<DD><CODE>callback</CODE> - OK�{�^�������ꍇ�̃R�[���o�b�N�֐��A�I�v�V�����B
</DL></DD>
</DL></DD>