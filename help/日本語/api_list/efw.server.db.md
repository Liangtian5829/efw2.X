<BR><TABLE BORDER="1" WIDTH="100%" CELLPADDING="3" CELLSPACING="0" SUMMARY="">
	<TR BGCOLOR="#CCCCFF" CLASS="TableHeadingColor">
		<TH ALIGN="left" COLSPAN="1"><FONT SIZE="+2"><B>efw.server.db�̏ڍ�</B></FONT></TH>
	</TR>
</TABLE>

<H3><A NAME="efw.server.db.open">open</A></H3>
<pre>
open ( <A href="#efw.sqlExecution.jdbcResourceName">jdbcResourceName</A> )</PRE>
<DL>
<DD>�f�[�^�x�[�X�ڑ����J���B
<P>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.sqlExecution.jdbcResourceName">jdbcResourceName</A></CODE> - jdbc���\�[�X�̖��́A������A�I�v�V�����B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="efw.server.db.getSingle">getSingle</A></H3>
<pre>
getSingle ( <A href="#efw.sqlExecution.executionParams">executionParams</A> )</PRE>
<DL>
<DD>SELECT�������s���āA�P�ڂ̃f�[�^��߂��B
<P>
<DD><DL>
<DT><B>�߂�l:</B>
<DD><CODE>���ʂ�����ꍇ�A<A href="#efw.sqlExecution.executionResult">executionResult</A></CODE> �̂P�s�ڃf�[�^�B
<DD><CODE>null</CODE> - ���ʂ��Ȃ��ꍇ�Anull ��߂��B
</DL></DD>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.sqlExecution.executionParams">executionParams</A></CODE> - SQL���s�p�p�����[�^�[�A�K�{�B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="efw.server.db.executeQuery">executeQuery</A></H3>
<pre>
executeQuery ( <A href="#efw.sqlExecution.executionParams">executionParams</A> )</PRE>
<DL>
<DD>SELECT�������s����B
<P>
<DD><DL>
<DT><B>�߂�l:</B>
<DD><CODE><A href="#efw.sqlExecution.executionResult">executionResult</A></CODE> - SQL�������ʁB
</DL></DD>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.sqlExecution.executionParams">executionParams</A></CODE> - SQL���s�p�p�����[�^�[�A�K�{�B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="efw.server.db.executeUpdate">executeUpdate</A></H3>
<pre>
executeUpdate ( <A href="#efw.sqlExecution.executionParams">executionParams</A> )</PRE>
<DL>
<DD>INSERT���AUPDATE���ADELETE�������s����B
<P>
<DD><DL>
<DT><B>�߂�l:</B>
<DD>���s���ꂽ�s����߂��B
</DL></DD>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.sqlExecution.executionParams">executionParams</A></CODE> - SQL���s�p�p�����[�^�[�A�K�{�B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="efw.server.db.execute">execute</A></H3>
<pre>
execute ( <A href="#efw.sqlExecution.executionParams">executionParams</A> )</PRE>
<DL>
<DD>�C�ӂ�SQL�������s����B
<P>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.sqlExecution.executionParams">executionParams</A></CODE> - SQL���s�p�p�����[�^�[�A�K�{�B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="efw.server.db.commit">commit</A></H3>
<pre>
commit ( <A href="#efw.sqlExecution.jdbcResourceName">jdbcResourceName</A> )</PRE>
<DL>
<DD>�f�[�^�x�[�X�ւ̍X�V��L���Ƃ��A �f�[�^�x�[�X�ڑ����ێ�����f�[�^�x�[�X���b�N�����ׂĉ�������B
<P>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.sqlExecution.jdbcResourceName">jdbcResourceName</A></CODE> - jdbc���\�[�X�̖��́A������A�I�v�V�����B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="efw.server.db.rollback">rollback</A></H3>
<pre>
rollback ( <A href="#efw.sqlExecution.jdbcResourceName">jdbcResourceName</A> )</PRE>
<DL>
<DD>�f�[�^�x�[�X�ւ̍X�V�𖳌��Ƃ��A �f�[�^�x�[�X�ڑ����ێ�����f�[�^�x�[�X���b�N�����ׂĉ�������B
<P>
<DD><DL>
<DT><B>�p�����[�^:</B>
<DD><CODE><A href="#efw.sqlExecution.jdbcResourceName">jdbcResourceName</A></CODE> - jdbc���\�[�X�̖��́A������A�I�v�V�����B
</DL></DD>
</DL></DD>
<HR>

<H3><A NAME="efw.server.db.closeAll">closeAll</A></H3>
<pre>
closeAll ( ) </PRE>
<DL>
<DD>���ׂẴf�[�^�x�[�X�ڑ��ɑ΂��āA�X�e�[�g�����g��S�����āA�f�[�^�x�[�X�ڑ����R�~�b�g���ĕ���B 
<P>
<DD><DL>
</DL></DD>
</DL></DD>