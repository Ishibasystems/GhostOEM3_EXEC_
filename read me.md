==============================================================================================================
     GhostOEM32 EXEC �� for SOTEC PX9512 VISTA Version 1.0 (2010/09/02) [VIA-1A-1]
                  �@�@�@�@�@�@�@�@�@�@�@                                      Copyright (C) 2010 HuIeji Utsuro
==============================================================================================================
				�@�@�@�@�@�@�@�@�@�@�@           WARNING : FOR HAND OUT AND USE IN JAPAN ONLY.

*�͂��߂�

  GhostOEM32 EXEC �� ���_�E�����[�h���������A���ɗL��������܂��B
  ���̃v���O������"SOTEC PX9512"�̃��J�o���f�B�X�N�쐬�̍ہAWindows AIK ���g�p���� Windows PE ��
  �������邱�Ƃɂ���ă��J�o���I�v�V�����̑I���EWindows �̃V���b�g�_�E�����s�Ȃ����̂ł��B

�@����������"SOTEC PX9512"�� vista(OS) �f�B�X�N�t���ĂȂ��A���J�o���f�B�X�N�t���ĂȂ��A���J�o���� HDD ����
    �����オ��Z�b�g�ɂȂ��Ă�񂾂��ǂ��A������� HDD ��񂾂�A�E�g����ˁH������

  �悤����Ƀ��J�o���f�B�X�N�����Ă��Ȃ� PC �ŁA���J�o���� HDD ����s�Ȃ��^�C�v�� PC ��
  ���J�o���f�B�X�N�� Windows AIK �� HSP �ō���Ă��܂����Ƃ������ł��B

  �����O��̃\�[�X+�v���O�����ł��������ɂ���Ă�USB����ł��N���E���J�o���N���\�ł��B
  ����ɉ������邱�Ƃɂ���đ���PC�ɂ��K���B���� Windows PE ��Ŏg����CUI���j���[��ʂȂǂɂ��ł��܂��B
  ������� Windows PE �́u��������ړI��OS���v���������Ƃ��O��ŁB

  Windows PE 2.0 �AWindows PE 3.0 �ɑΉ��m�F�B
  (32bit�I�����[�B����� hsp ��32bit�v���O����������BWindows PE 64bit ��ɂ� WOW64 ���Ȃ��̂œ����܂���B
   ���ɂȂ����� 64bit��hsp �o��񂾁H Windows 7 64bit�̏C���f�B�X�N��(WOW64�Ȃ�)�Ƃ����v����̂ɁB)


*�J����

�@���̃v���O������
�@�@Microsoft Windows 7 64bit
�@�@onion software HSP script editer for Windows ver3.1
�@�̊��ŊJ�����܂����B


*�����

  Microsoft Windows PE 2.0 ������m�F�B
  Microsoft Windows PE 3.0 ������m�F�B
  (���ׂē��{���32bit)


*�t�@�C���\��

�@px9512.exe 		���s�t�@�C��
  px9512.hsp		�\�[�X�t�@�C��
  read me!.txt		���̃t�@�C��

�@���̃\�t�g�̓��W�X�g������؎g���܂���(�܂� Windows PE ��ŏ�������ł��ċN����������񂾂��ǂ�)�B


*�g����

  ���J�o���ŏ�����(SOTEC PX9512)

	��)HDD �� HDREC �p�[�e�B�V�������� GhostOEM32.exe �� GDisk32.exe �A
	   vista.img vista.001 vista.002 data.img ������܂��B
	   ���炩���� Ubuntu �ȂǂŃR�s�[���ē��肵�Ă����܂��B

	�܂� Windows AIK (Windows�����C���X�g�[���L�b�g)���C���X�g�[�����܂��B
	http://www.microsoft.com/downloads/details.aspx?familyid=696DD665-9F76-4177-A811-39C26D3B3B34&displaylang=ja
	(2010/09/01�m�F)

	Windows 7 �p�ł�����肠��܂���B

	�����͂��ꂾ���ł����B�ȍ~�͖���s�Ȃ��܂��B

	�@Windows Vista�AWindows 7 �p GhostOEM32 EXEC �� for SOTEC PX9512 VISTA �g�ݍ��ݖ@

	�E[�X�^�[�g]��[���ׂẴv���O����]��[Microsoft Windows AIK]��[Deployment �c�[���̃R�}���h �v�����v�g] ���N���B

	�EWindows PE �r���h�����쐬���܂��B
	  �R�}���h�v�����v�g�ɉ��L�̃R�}���h����́A[Enter]�B

	  copype x86 C:\winpe

	  ��)�쐬�ꏊ��C:\������C:\winpe�ɂ��Ă��܂��B���łɓ����t�H���_���̃t�H���_������ƃG���[���܂��B
	     �܂�hsp,ghost32�n,gdisk32�n��32bit�v���O�����ł��̂�"x86"�ȊO�����܂���B

	�EC:\winpe\winpe.wim ���R�s�[�AC:\winpe\boot.wim ���쐬���܂��B

	�EC:\winpe\boot.wim �� C:\winpe\mount �t�H���_�ɓW�J���܂��B
	  �R�}���h�v�����v�g�ɉ��L�̃R�}���h����́A[Enter]�B

	  dism /mount-wim /wimfile:C:\winpe\boot.wim /index:1 /mountdir:C:\winpe\mount

	�EC:\winpe\mount\Program Files�t�H���_���� tools �t�H���_���쐬�A���̒��� px9512.exe ��
	  GhostOEM32.exe �� GDisk32.exe ���R�s�[���܂��B

	  ��)�܂��č\�����Ƀt�@�C����������܂��̂ňړ��łȂ��R�s�[�����B

	�EC:\winpe\mount\Windows\System32�t�H���_���� startnet.cmd ���E�N���b�N��[�ҏW(E)]�B
	  ���L�̃R�}���h���Ō�̍s�ɒǉ����ۑ����܂��B

	  "%PROGRAMFILES%\tools\px9512.exe"

	  ��) wpeinit �� Windows PE �̏������ɕK�v�Ȃ̂ŏ����Ȃ��ł��������B

	�EC:\winpe\boot.wim �� C:\winpe\mount �t�H���_����č\�����܂��B
	  �R�}���h�v�����v�g�ɉ��L�̃R�}���h����́A[Enter]�B

	  ImageX /unmount /commit C:\winpe\mount

	  ��)C:\winpe\mount�ȉ��̃t�H���_�E�t�@�C������Ă�����s���Ă��������B

	�EC:\winpe\boot.wim �� C:\winpe\ISO\sources �t�H���_�Ɉړ����܂��B

	�E�K�v�ȃC���[�W�t�@�C�� vista.img vista.001 vista.002 data.img �� C:\winpe\ISO �t�H���_�ɃR�s�[���܂��B

	�Eiso �C���[�W���\�����܂��B
	  �R�}���h�v�����v�g�ɉ��L�̃R�}���h����́A[Enter]�B

	  oscdimg -m -n -bC:\winpe\etfsboot.com C:\winpe\ISO C:\winpe\winpe.iso

	�EC:\winpe\winpe.iso��DVD�ɏĂ��Ċ����B

	  ��) �e�ʂ�5GB���Ȃ̂œ�wDVD�ɂȂ�܂��B

	�A�f�B�X�N�̎g����

	�EPC�Ƀf�B�X�N�����ċN�����܂��B
	  ��ʂ�

	  Press any key to boot from CD or DVD.

	  �ƕ\�����ꂽ��[Enter]�B

	  ��) �\������Ȃ��ꍇ�ċN�����Ă݂Ă��������B
	      ����ł��\������Ȃ��ꍇ�ABIOS�̐ݒ��ύX����K�v������܂��B

	�E�����قǂ�px9512.exe�������N�����ďC�����j���[���o���܂��B
	  �K�v�ȏ��������j���[����I��Ŕԍ�����́A[Enter]�B

	�E���̌�͕\���̒ʂ葀��E�C�����ăV���b�g�_�E�����܂��B


  SOTEC PX9512 �ȊO�ւ̉��p�@

	�����А�PC���l�����Đ������܂��B

	�E�܂����J�o�����삷��ہA�ǂ̃p�[�e�B�V��������ǂ̃v���O�������Ăяo����Ă���̂��������܂��B
	  (���J�o���v���O����(Symantec Ghost�Ȃ�)���w�������Ȃ炻��Ō��\�B)

	  �����Ă��̏ꍇ�B���p�[�e�B�V�������Ƀf�[�^���i�[����Ă���̂Ńp�[�e�B�V������S�����Ă݂܂��B

	  [�R���g���[���p�l��]��[�Ǘ��c�[��]��[�R���s���[�^�[�̊Ǘ�]��[�f�B�X�N�̊Ǘ�]
	  �{�����[���̉���(C:)�Ȃǂ��o�܂����������̃{�����[������������B���p�[�e�B�V�����ł��B
	  �E�N���b�N��[�h���C�u�����ƃp�X�̕ύX(C)...]��[�ǉ�(D)...]�Ŏg���Ă��Ȃ��h���C�u������I���B
	  [OK]�������ƉB���p�[�e�B�V�������w�肵���h���C�u�����ɂȂ�L���ɂȂ�܂��B
	  ���J�o���Ɏg���Ă������ȃf�[�^(exe�t�@�C��)�Ƃ��̎��ӂ̃t�@�C����ʃh���C�u�ɃR�s�[���Ă����܂��B

	  ��)PX9512�̏ꍇ�A[HDREC]�Ƃ����p�[�e�B�V��������recover2.exe�B
	     �N�����Ă݂��炻�̂܂܃��J�o����ʂ�������
	     ���J�o���f�[�^���ǂꂩ�킩��Ȃ������̂Ńp�[�e�B�V�������̑S�t�@�C�����R�s�[�B

	  �������葁�� Ubuntu �� HDD ��`���ĉB���p�[�e�B�V������������@������܂��B

	  ��)�u�[�g���[�_�[�p�[�e�B�V�����̉\��������̂ŃR�s�[���삾���ɂƂǂ߂Ă����܂��B
	     �������PC���N�����Ȃ��Ȃ錴���ƂȂ�\��������B

	�E���J�o���v���O�����ɓn�����R�}���h���C���𒲂ׂ܂��B
	  (���J�o���v���O����(Symantec Ghost�Ȃ�)�ɓn���R�}���h��m���Ă�Ȃ炻��Ō��\�B)

	  ��)recover2.exe ���������Ō���ƕ��ʂɕW���E���x1�E���x2��3��R�}���h���C���𔭌��B

	  �������̕��@�Ō�����΂����̂ł����c
	  �u�[�g���[�_�[�����ڃ��J�o���v���O�������Ă񂾂肷��Ƃǂ����Ă�������Ȃ������肷��̂ŁA
	  ������Ȃ��ꍇ�̓��J�o���v���O�����̑���Ƀ_�~�[�v���O������u���ă��J�o�������s���Ă݂�
	  �R�}���h���C����f�����܂��B

	�E(���C���C�x���g)px9512.hsp���������܂��B

	  ��)�R���\�[��hsp(hsp3cl)�ł��邱�Ƃɒ��ӁBstick�����g���܂���B

	  �X�N���v�g���ɊȈՐ���������܂��B
	  �������j���̒񎦁E���̃v���O�����Ăяo���E�I���������ĂȂ��̂�
	  ���܂ł̐����������ł��郆�[�U�[�Ȃ��̂͂킩��Ǝv���܂��B

	  ���̃X�N���v�g��������GUI�ɂ��Ă������񂶂�Ȃ��H
	  �����͂�����ꂽ�B�e������wDVD�����Ă���Ȃ����B

  ������̑���ɂ���A��襋^�₪�������܂������҂܂ł��₢���킹���������B


*����

	�g�p�����_��

	�ȉ����uGhostOEM32 EXEC �� for SOTEC PX9512 VISTA�v���u�{�\�t�g�E�F�A�v�A
        �u�s�ƘH���v���u���v�A�@�l�A�l���킸�u�{�\�t�g�E�F�A�g�p�ҁv���u�g�p�ҁv�ƋL�ڂ������܂��B

	���̃v���O�����͓��{���������̔z�z�A�y�юg�p�Ƃ��܂��B
	FOR HAND OUT AND USE IN JAPAN ONLY.
	����ȊO�ł̎g�p�͉����̕ۏ؊O�ƂȂ�܂��B

	1.���쌠�ɂ���

	NYSL Version 0.9982 + E (�Ǎ�)

	A. �{�\�t�g�E�F�A�� Everyone'sWare �ł��B���̃\�t�g����ɂ�����l��l���A
	   �������̍�������̂������̂Ɠ����悤�ɁA���R�ɗ��p���邱�Ƃ��o���܂��B

	  A-1. �t���[�E�F�A�ł��B��҂���͎g�p������v�����܂���B
	  A-2. �L��������}�̂̔@�����킸�A���R�ɓ]�ځE�Ĕz�z�ł��܂��B
	  A-3. �����Ȃ��ނ� ���ρE���v���O�����ł̗��p ���s���Ă��\���܂���B
	  A-4. �ύX�������̂╔���I�Ɏg�p�������̂́A���Ȃ��̂��̂ɂȂ�܂��B
	       ���J����ꍇ�́A���Ȃ��̖��O�̉��ōs���ĉ������B

	B. ���̃\�t�g�𗘗p���邱�Ƃɂ���Đ��������Q���ɂ��āA��҂�
	   �ӔC�𕉂�Ȃ����̂Ƃ��܂��B�e���̐ӔC�ɂ����Ă����p�������B

	C. ����Ґl�i���� �s�ƘH�� �ɋA�����܂��B���쌠�͕������܂��B

	D. �ȏ�̂R���́A�\�[�X�E���s�o�C�i���̑o���ɓK�p����܂��B

	E. �R���p�C���v��

	 �{�\�t�g�E�F�A�́A

	�@onion software HSP script editer for Windows version 3.1
	�@Copyright (C) 1997-2007 onion Software
	�@(http://www.onionsoft.net/hsp/)

	 �ɂ���ăR���p�C������Ă��܂��B�܂�

	  �Ⓚ�^ 1.12b2 with UPX 3.03w

	 �@UPX (The Ultimate Packer for eXecutables)
	�@ Copyright (c) 1996-2000 Markus Oberhumer & Laszlo Molnar
	�@ (http://upx.sourceforge.net/)

	   �Ⓚ�^
	   Copyright (C) 2009 - 2010 �΋��ˑ�
	   (http://ishibasystems.ikaduchi.com/)

	 �ň��k����Ă��܂��B

	 ���ꂼ��̃\�t�g�E�F�A�̒��쌠�͂��ꂼ��̍�҂ɋA�����܂��B

	2.�֎~����

	 �{�\�t�g�E�F�A�͈�@�ȍs�ׁAWindows PE�EWindows AIK�E���̑� Windows OS ����
         ���C�Z���X�K��ᔽ�ɂȂ�Ȃ��悤�Ɏg�p���Ă��������B

	3.�z�z�Ɋւ��鐧���ɂ���

	 ������݂��܂���B

	4.�z�z�Ɋւ��錠���ɂ���

	 ? �����ˁA���ɁB

	5.�z�z�Ɋւ��邨�肢�ɂ���

	 �z�z�̍ۂɍ�҂ɘA�����Ă����Ƒ��т��܂���i�O�O�j�B
 
	6.�Ɛӥ�ۏ؂ɂ���

	 ���́A�{�\�t�g�E�F�A�Ɋւ��āA�@�������r�S�ېӔC�A���i�������
	 ����̖ړI�ւ̓K�����̕ۏ؁A���̑���؂̕ۏ؂��������܂���B


*���₢���킹

  ���ӌ��A�s��̏��A�v�]�A���z�Ȃǂ��ł����҂����Ă��܂��B

�@home page	http://ishibasystems.ikaduchi.com/
�@e-mail	http://ishibasystems.ikaduchi.com/mail.html

*�X�V����

[2010/09/02]	������̊J���J�n

[2009/09/04]	VIA-1A-1 version 1.0 ���J
	�J���B

����Ґl�i�� HuIeji Utsuro , Ishibasystems Software.

[EOF]