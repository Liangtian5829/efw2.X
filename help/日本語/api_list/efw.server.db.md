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

<H3><A NAME="efw.sqlExecution.jdbcResourceName">jdbcResourceName</A></H3>
<pre>
jdbcResourceName = "jdbc/efw" ;                                                 //server.xml�ɒ�`����郊�\�[�X

&lt;Resource auth="Container" driverClassName="org.postgresql.Driver" 
maxActive="100" maxIdle="20" maxWait="10" name="jdbc/efw" password="postgres" 
type="javax.sql.DataSource" url="jdbc:postgresql://127.0.0.1:5432/efwSample" 
username="postgres"/&gt;
</PRE>
<DL><DD>jdbc�̃��\�[�X���B<br>
efw�̃f�B�t�H���g���\�[�X�́Ajdbc/efw �B����ȊO�̃��\�[�X�𗘗p�������ꍇ�A<br>
server.xml�ɒ�`���āA�C�x���gjs�t�@�C���ɁA����� open ���āA�g�����U�N�V�������Ǘ�����B

</DL></DD>

<BR><TABLE BORDER="1" WIDTH="100%" CELLPADDING="3" CELLSPACING="0" SUMMARY="">
	<TR BGCOLOR="#CCCCFF" CLASS="TableHeadingColor">
		<TH ALIGN="left" COLSPAN="1"><FONT SIZE="+2"><B>SQL execution�̏ڍ�</B></FONT></TH>
	</TR>
</TABLE>

<H3><A NAME="efw.sqlExecution.executionParams">executionParams</A></H3>
<pre>
executionParams = {
                      <a href="#efw.sqlExecution.jdbcResourceName">jdbcResourceName</a> : "jdbc/efw",                            //jdbc���\�[�X���A�I�v�V�����B
                      groupId          : "user",                                //sqlXML�t�@�C�����A�K�{�B
                      sqlId            : "selectusers",                         //SQL��Id�A�K�{�B
                      params           : {                                      //SQL�p�����[�^�[�A�K�{�B
                                             sqlparam1 : value1 ,
                                             sqlparma2 : value2 ,
                                         },
                      mapping          : {                                      //�}�b�s���O�A�I�v�V�����B����SQL�̌������ʃt�B�[���h����ʍ��ڂ܂��̓}�X�N�L�[�ƃ}�b�s���O����B
                                             selector1 : field1 ,
                                             selector2 : [ Datefield , formatter ] ,             //���t�t�B�[���h���t�H�[�}�b�g���Ă���}�b�s���O�B
                                             selector3 : [ Numberfield , formatter , rounder ] , //�����t�B�[���h���t�H�[�}�b�g���Ă���}�b�s���O�B�K�v�ł���Ίۂ݃^�C�v���w��\�B
                                             selector4 : function(rs){ ... },   //�������ʂ̃��R�[�h����l���Z�o���ă}�b�s���O����B
                                         },
                  };
</PRE>
<DL><DD>SQL���s�p�p�����[�^�[�B<br>
SQL�����s���邽�߁AXML�t�@�C���ɒ�`����SQL�̃p�����[�^�[�̒l��ݒ�B�܂����s���ʂ̃}�b�s���O���ݒ�B<br>

</DL></DD>
<HR>

<H3><A NAME="efw.sqlExecution.executionResult">executionResult</A></H3>
<pre>
executionResult = [                                                             //�}�b�s���O�Ȃ��̎��s���ʁAfield���ڂƒl�̃Z�b�g�̔z��B
                    {                                                           //�ЂƂ̃��R�[�h�B
                      field1 : value1 ,
                      field2 : value2 ,
                    },
                  ];
                  
executionResult = [                                                             //selector�ƃ}�b�s���O������s���ʁAselector���ڂƒl�̃Z�b�g�̔z��B
                    {                                                           //�ЂƂ̃��R�[�h�B
                      selector1 : value1 ,
                      selector2 : value2 ,
                    },
                  ];

executionResult = [                                                             //maskKey�ƃ}�b�s���O������s���ʁAmaskKey���ڂƒl�̃Z�b�g�̔z��B
                    {                                                           //�ЂƂ̃��R�[�h�B
                      maskKey1 : value1 ,
                      maskKey2 : value2 ,
                    },
                  ];
</PRE>
<DL><DD>SQL�������ʁB<br>
executeQuery�̎��s���ʁB���R�[�h�Z�b�g�̔z��B�������ʂ��Ȃ��ꍇ�A��̔z��ɂȂ�B<br>
�}�b�s���O�̗L���ɂ��A�ω����\�B

</DL></DD>
<HR>


<H3><A NAME="efw.sqlExecution.jdbcResourceName">jdbcResourceName</A></H3>
<pre>
jdbcResourceName = "jdbc/efw" ;                                                 //server.xml�ɒ�`����郊�\�[�X

&lt;Resource auth="Container" driverClassName="org.postgresql.Driver" 
maxActive="100" maxIdle="20" maxWait="10" name="jdbc/efw" password="postgres" 
type="javax.sql.DataSource" url="jdbc:postgresql://127.0.0.1:5432/efwSample" 
username="postgres"/&gt;
</PRE>
<DL><DD>jdbc�̃��\�[�X���B<br>
efw�̃f�B�t�H���g���\�[�X�́Ajdbc/efw �B����ȊO�̃��\�[�X�𗘗p�������ꍇ�A<br>
server.xml�ɒ�`���āA�C�x���gjs�t�@�C���ɁA����� open ���āA�g�����U�N�V�������Ǘ�����B

</DL></DD>
