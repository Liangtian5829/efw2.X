<a href="../api_list.md">�߂�</a>
&nbsp;&nbsp;&nbsp;&nbsp;<a href="../../���{��/api_list/efw.client.md">���{��</a>
&nbsp;<a href="../../����/api_list/efw.client.md">����</a>
&nbsp;<a href="../../English/api_list/efw.client.md">English</a>
<H2>efw.client�̏ڍ�</H2>
<HR>


<H3><A NAME="fire">fire</A></H3>
<pre>
fire ( <A href="#eventParams">eventParams</A> )</PRE>
<DL>
<DD>Ajax���Ăяo�����߂̓�����֐��B
 1���Ajax�̓p�����[�^�[�t�H�[�}�b�g���擾���A2���Ajax�����s����B
<P>
<DD><DL>
<B>�p�����[�^:</B>
<DD><CODE><A href="#eventParams">eventParams</A></CODE> - �C�x���g�p�����[�^�[�A�K�{�B
</DL></DD>
<HR>

<H3><A NAME="pickup">pickup</A></H3>
<pre>
pickup ( <A href="#efw.event.paramsFormat">paramsFormat</A> , <A href="#manualParams">manualParams</A> )</PRE>
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
<DD><CODE><A href="#manualParams">manualParams</A></CODE> - �蓮�p�����[�^�[ �A�I�v�V�����B
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
<HR>

<H3><A NAME="eventParams">eventParams</A></H3>
<pre>
eventParams = {
                  <A href="#server">server</A>       : "http://127.0.0.1:8080/efwTest",               //�T�[�oURL�A�I�v�V�����B
                  <A href="#eventId">eventId</A>      : "myEvent",                                     //�C�x���gId�A�K�{�B
                  <A href="#manualParams">manualParams</A> : {                                              //�蓮�p�����[�^�[�A�I�v�V�����B
                                     key1 : value1,
                                     key2 : value2,    
                                 },
                  <A href="#success">success</A>      : function ( <A href="#efw.event.fire.eventResult">eventResult</A> ) {                    //�����R�[���o�b�N�֐��A�I�v�V�����B
                                     ...
                                 },
              };
</PRE>
<DL><DD>�C�x���g�p�����[�^�[�B�N���C�A���g�ŃC�x���g�����s���쐬�����B
<br>�E�C�x���gId�ɂ��C�x���g����肷��B
<br>�E�p�����[�^�[�t�H�[�}�b�g�ɂ��C�x���g�p�����[�^�[���쐬���A�D��I�ɃN���C�A���g��ʂ���l���擾����B��ʍ��ڂł͂Ȃ��ꍇ�A�蓮�p�����[�^�[�œn���B
<br>�E�C�x���g���s������A����Ɍp���������K�v�ȏꍇ�A�����R�[���o�b�N�֐��𗘗p����B

</DL></DD>
<HR>

<H3><A NAME="server">server</A></H3>
<pre>
server = "http://127.0.0.1:8080/efwTest",                                       //�T�[�oURL�A�I�v�V�����B
</PRE>
<DL><DD>�T�[�oURL�Bcors�����ő��̃T�[�o�A�v���Ɛڑ�����ꍇ���p�ł���B
</DL></DD>
<HR>


<H3><A NAME="eventId">eventId</A></H3>
<pre>
eventId = "myEvent";                                                            // WEB-INF/efw/event/myEvent.js ��js�t�@�C���ƃ����N����B�p��̑啶������������ʁB
</PRE>
<DL><DD>�C�x���gId�B�C�x���g�̎��������T�[�o�[�T�C�hJavascript�t�@�C�����Ɠ����B
</DL></DD>
<HR>


<H3><A NAME="manualParams">manualParams</A></H3>
<pre>
manualParams = {
                   key1 : value1,
                   key2 : value2,
               };
</PRE>
<DL><DD>�蓮�p�����[�^�[�B�C�x���g�Ɏ蓮�œn�������p�����[�^�[��ݒ肷��B
</DL></DD>
<HR>


<H3><A NAME="success">success</A></H3>
<pre>
success = function ( <A href="#efw.event.fire.eventResult">eventResult</A> ) { ... };
</PRE>
<DL><DD>�����R�[���o�b�N�֐��B<br>
�C�x���g�����������̏ꍇ�A���s�����B���̒i�K�ŁAeventResult �͂��łɉ�ʂɔ��f�����B<br>�܂�Asuccess�֐��� eventResult �ɑ΂��ďC�����Ă��Ӗ����Ȃ��B
</DL></DD>
