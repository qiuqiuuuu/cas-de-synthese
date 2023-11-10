<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_ujXmUH-lEe6rdachP4tzAw" name="ORACLE" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_ujXmUX-lEe6rdachP4tzAw" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_ujXmUn-lEe6rdachP4tzAw" value="CSG1_ORA2"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_ujXmU3-lEe6rdachP4tzAw" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_ujXmVH-lEe6rdachP4tzAw" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_ujXmVX-lEe6rdachP4tzAw" value="6F23E4E8A3281AF328EB08370AA8572A"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_ujXmVn-lEe6rdachP4tzAw" value="jdbc:oracle:thin:@195.83.93.26:1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_ujXmV3-lEe6rdachP4tzAw" name="CSG1_ORA2">
    <attribute defType="com.stambia.rdbms.schema.name" id="_ujXmWH-lEe6rdachP4tzAw" value="CSG1_ORA2"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_ujXmWX-lEe6rdachP4tzAw" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_ujXmWn-lEe6rdachP4tzAw" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_ujXmW3-lEe6rdachP4tzAw" value="I_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_ujXmXH-lEe6rdachP4tzAw" name="SAS_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ujXmXX-lEe6rdachP4tzAw" value="SAS_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ujXmXn-lEe6rdachP4tzAw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ujXmX3-lEe6rdachP4tzAw" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmYH-lEe6rdachP4tzAw" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmYX-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmYn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmY3-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmZH-lEe6rdachP4tzAw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmZX-lEe6rdachP4tzAw" name="CLE_COMPTE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmZn-lEe6rdachP4tzAw" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmZ3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmaH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmaX-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXman-lEe6rdachP4tzAw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXma3-lEe6rdachP4tzAw" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmbH-lEe6rdachP4tzAw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmbX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujXmbn-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmb3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmcH-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmcX-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmcn-lEe6rdachP4tzAw" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmc3-lEe6rdachP4tzAw" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmdH-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujXmdX-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmdn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmd3-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmeH-lEe6rdachP4tzAw" value="2"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmeX-lEe6rdachP4tzAw" name="CIVILITE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmen-lEe6rdachP4tzAw" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXme3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujXmfH-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmfX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmfn-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmf3-lEe6rdachP4tzAw" value="2"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmgH-lEe6rdachP4tzAw" name="PRENOM" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmgX-lEe6rdachP4tzAw" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmgn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmg3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmhH-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmhX-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmhn-lEe6rdachP4tzAw" name="NOM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmh3-lEe6rdachP4tzAw" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmiH-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmiX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmin-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmi3-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmjH-lEe6rdachP4tzAw" name="DATE_ANNIVERSAIRE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmjX-lEe6rdachP4tzAw" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmjn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmj3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmkH-lEe6rdachP4tzAw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmkX-lEe6rdachP4tzAw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmkn-lEe6rdachP4tzAw" name="SEXE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmk3-lEe6rdachP4tzAw" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmlH-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujXmlX-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmln-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXml3-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmmH-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmmX-lEe6rdachP4tzAw" name="MUTUELLE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmmn-lEe6rdachP4tzAw" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmm3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujXmnH-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmnX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmnn-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmn3-lEe6rdachP4tzAw" value="2"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmoH-lEe6rdachP4tzAw" name="NOM_FICHIER" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmoX-lEe6rdachP4tzAw" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXmon-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmo3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmpH-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujXmpX-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_ujXmpn-lEe6rdachP4tzAw" name="SYS_C0015442">
        <node defType="com.stambia.rdbms.colref" id="_ujXmp3-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_ujXmqH-lEe6rdachP4tzAw" ref="resource.md#_ujXmX3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujXmqX-lEe6rdachP4tzAw" name="SYS_C0015419">
        <node defType="com.stambia.rdbms.relation" id="_ujXmqn-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujXmq3-lEe6rdachP4tzAw" ref="resource.md#_ujXmoH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujXmrH-lEe6rdachP4tzAw" ref="resource.md#_ujYNqn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujXmrX-lEe6rdachP4tzAw" name="SYS_C0015418">
        <node defType="com.stambia.rdbms.relation" id="_ujXmrn-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujXmr3-lEe6rdachP4tzAw" ref="resource.md#_ujXmZX-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_COMPTE?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujXmsH-lEe6rdachP4tzAw" ref="resource.md#_ujY0fn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmsX-lEe6rdachP4tzAw" name="ID_FICHIER" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujXmsn-lEe6rdachP4tzAw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujXms3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujXmtH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujXmtX-lEe6rdachP4tzAw" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujXmtn-lEe6rdachP4tzAw" name="DATE_IMPORT" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNYH-lEe6rdachP4tzAw" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNYX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNYn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNY3-lEe6rdachP4tzAw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNZH-lEe6rdachP4tzAw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYNZX-lEe6rdachP4tzAw" name="SYS_C0015443">
        <node defType="com.stambia.rdbms.relation" id="_ujYNZn-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYNZ3-lEe6rdachP4tzAw" ref="resource.md#_ujXmZX-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_COMPTE?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYNaH-lEe6rdachP4tzAw" ref="resource.md#_ujY0fn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYNaX-lEe6rdachP4tzAw" name="SYS_C0015444">
        <node defType="com.stambia.rdbms.relation" id="_ujYNan-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYNa3-lEe6rdachP4tzAw" ref="resource.md#_ujXmsX-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYNbH-lEe6rdachP4tzAw" ref="resource.md#_ujY0uH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ujYNbX-lEe6rdachP4tzAw" name="SAS_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ujYNbn-lEe6rdachP4tzAw" value="SAS_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ujYNb3-lEe6rdachP4tzAw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ujYNcH-lEe6rdachP4tzAw" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNcX-lEe6rdachP4tzAw" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNcn-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNc3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNdH-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNdX-lEe6rdachP4tzAw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNdn-lEe6rdachP4tzAw" name="EMAIL" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNd3-lEe6rdachP4tzAw" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNeH-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNeX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNen-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNe3-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNfH-lEe6rdachP4tzAw" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNfX-lEe6rdachP4tzAw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNfn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujYNf3-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNgH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNgX-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNgn-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNg3-lEe6rdachP4tzAw" name="NOM_FICHIER" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNhH-lEe6rdachP4tzAw" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNhX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNhn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNh3-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNiH-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_ujYNiX-lEe6rdachP4tzAw" name="SYS_C0015445">
        <node defType="com.stambia.rdbms.colref" id="_ujYNin-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_ujYNi3-lEe6rdachP4tzAw" ref="resource.md#_ujYNcH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYNjH-lEe6rdachP4tzAw" name="SYS_C0015421">
        <node defType="com.stambia.rdbms.relation" id="_ujYNjX-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYNjn-lEe6rdachP4tzAw" ref="resource.md#_ujYNcH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYNj3-lEe6rdachP4tzAw" ref="resource.md#_ujXmX3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYNkH-lEe6rdachP4tzAw" name="SYS_C0015422">
        <node defType="com.stambia.rdbms.relation" id="_ujYNkX-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYNkn-lEe6rdachP4tzAw" ref="resource.md#_ujYNg3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYNk3-lEe6rdachP4tzAw" ref="resource.md#_ujYNqn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNlH-lEe6rdachP4tzAw" name="ID_FICHIER" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNlX-lEe6rdachP4tzAw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNln-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNl3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNmH-lEe6rdachP4tzAw" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNmX-lEe6rdachP4tzAw" name="DATE_IMPORT" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNmn-lEe6rdachP4tzAw" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNm3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNnH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNnX-lEe6rdachP4tzAw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNnn-lEe6rdachP4tzAw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYNn3-lEe6rdachP4tzAw" name="SYS_C0015447">
        <node defType="com.stambia.rdbms.relation" id="_ujYNoH-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYNoX-lEe6rdachP4tzAw" ref="resource.md#_ujYNlH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYNon-lEe6rdachP4tzAw" ref="resource.md#_ujY0uH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYNo3-lEe6rdachP4tzAw" name="SYS_C0015446">
        <node defType="com.stambia.rdbms.relation" id="_ujYNpH-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYNpX-lEe6rdachP4tzAw" ref="resource.md#_ujYNcH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYNpn-lEe6rdachP4tzAw" ref="resource.md#_ujXmX3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ujYNp3-lEe6rdachP4tzAw" name="SAS_SOURCE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ujYNqH-lEe6rdachP4tzAw" value="SAS_SOURCE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ujYNqX-lEe6rdachP4tzAw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ujYNqn-lEe6rdachP4tzAw" name="NOM_FICHIER" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNq3-lEe6rdachP4tzAw" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNrH-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNrX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNrn-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNr3-lEe6rdachP4tzAw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNsH-lEe6rdachP4tzAw" name="NB_LIGNE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNsX-lEe6rdachP4tzAw" value="NB_LIGNE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNsn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujYNs3-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNtH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNtX-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNtn-lEe6rdachP4tzAw" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNt3-lEe6rdachP4tzAw" name="DATE_CREATION" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNuH-lEe6rdachP4tzAw" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNuX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNun-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNu3-lEe6rdachP4tzAw" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_ujYNvH-lEe6rdachP4tzAw" name="SYS_C0015414">
        <node defType="com.stambia.rdbms.colref" id="_ujYNvX-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_ujYNvn-lEe6rdachP4tzAw" ref="resource.md#_ujYNqn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ujYNv3-lEe6rdachP4tzAw" name="SAS_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ujYNwH-lEe6rdachP4tzAw" value="SAS_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ujYNwX-lEe6rdachP4tzAw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ujYNwn-lEe6rdachP4tzAw" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNw3-lEe6rdachP4tzAw" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNxH-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNxX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNxn-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNx3-lEe6rdachP4tzAw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNyH-lEe6rdachP4tzAw" name="STATUS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYNyX-lEe6rdachP4tzAw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYNyn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujYNy3-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYNzH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYNzX-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYNzn-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYNz3-lEe6rdachP4tzAw" name="LIGNE_1" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYN0H-lEe6rdachP4tzAw" value="LIGNE_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYN0X-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYN0n-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYN03-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYN1H-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYN1X-lEe6rdachP4tzAw" name="LIGNE_2" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYN1n-lEe6rdachP4tzAw" value="LIGNE_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYN13-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYN2H-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYN2X-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYN2n-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYN23-lEe6rdachP4tzAw" name="LIGNE_3" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYN3H-lEe6rdachP4tzAw" value="LIGNE_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYN3X-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYN3n-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYN33-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYN4H-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYN4X-lEe6rdachP4tzAw" name="LIGNE_4" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYN4n-lEe6rdachP4tzAw" value="LIGNE_4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYN43-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYN5H-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYN5X-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYN5n-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYN53-lEe6rdachP4tzAw" name="LIGNE_5" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYN6H-lEe6rdachP4tzAw" value="LIGNE_5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYN6X-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYN6n-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYN63-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYN7H-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYN7X-lEe6rdachP4tzAw" name="VILLE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYN7n-lEe6rdachP4tzAw" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYN73-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYN8H-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYN8X-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYN8n-lEe6rdachP4tzAw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYN83-lEe6rdachP4tzAw" name="CODE_POSTAL" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYN9H-lEe6rdachP4tzAw" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYN9X-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYN9n-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYN93-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYN-H-lEe6rdachP4tzAw" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYN-X-lEe6rdachP4tzAw" name="PAYS" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYN-n-lEe6rdachP4tzAw" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYN-3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujYN_H-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYN_X-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYN_n-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYN_3-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOAH-lEe6rdachP4tzAw" name="QUALITE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOAX-lEe6rdachP4tzAw" value="QUALITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOAn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujYOA3-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOBH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOBX-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYOBn-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOB3-lEe6rdachP4tzAw" name="NOM_FICHIER" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOCH-lEe6rdachP4tzAw" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOCX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOCn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOC3-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYODH-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_ujYODX-lEe6rdachP4tzAw" name="SYS_C0015448">
        <node defType="com.stambia.rdbms.colref" id="_ujYODn-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_ujYOD3-lEe6rdachP4tzAw" ref="resource.md#_ujYNwn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYOEH-lEe6rdachP4tzAw" name="SYS_C0015424">
        <node defType="com.stambia.rdbms.relation" id="_ujYOEX-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYOEn-lEe6rdachP4tzAw" ref="resource.md#_ujYNwn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYOE3-lEe6rdachP4tzAw" ref="resource.md#_ujXmX3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYOFH-lEe6rdachP4tzAw" name="SYS_C0015425">
        <node defType="com.stambia.rdbms.relation" id="_ujYOFX-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYOFn-lEe6rdachP4tzAw" ref="resource.md#_ujYOB3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYOF3-lEe6rdachP4tzAw" ref="resource.md#_ujYNqn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOGH-lEe6rdachP4tzAw" name="ID_FICHIER" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOGX-lEe6rdachP4tzAw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOGn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOG3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOHH-lEe6rdachP4tzAw" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOHX-lEe6rdachP4tzAw" name="DATE_IMPORT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOHn-lEe6rdachP4tzAw" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOH3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOIH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOIX-lEe6rdachP4tzAw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYOIn-lEe6rdachP4tzAw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYOI3-lEe6rdachP4tzAw" name="SYS_C0015450">
        <node defType="com.stambia.rdbms.relation" id="_ujYOJH-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYOJX-lEe6rdachP4tzAw" ref="resource.md#_ujYOGH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYOJn-lEe6rdachP4tzAw" ref="resource.md#_ujY0uH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYOJ3-lEe6rdachP4tzAw" name="SYS_C0015449">
        <node defType="com.stambia.rdbms.relation" id="_ujYOKH-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYOKX-lEe6rdachP4tzAw" ref="resource.md#_ujYNwn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYOKn-lEe6rdachP4tzAw" ref="resource.md#_ujXmX3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ujYOK3-lEe6rdachP4tzAw" name="SAS_TEL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ujYOLH-lEe6rdachP4tzAw" value="SAS_TEL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ujYOLX-lEe6rdachP4tzAw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ujYOLn-lEe6rdachP4tzAw" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOL3-lEe6rdachP4tzAw" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOMH-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOMX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOMn-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYOM3-lEe6rdachP4tzAw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYONH-lEe6rdachP4tzAw" name="PHONE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYONX-lEe6rdachP4tzAw" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYONn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYON3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOOH-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYOOX-lEe6rdachP4tzAw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOOn-lEe6rdachP4tzAw" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOO3-lEe6rdachP4tzAw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOPH-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujYOPX-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOPn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOP3-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYOQH-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOQX-lEe6rdachP4tzAw" name="FAVORI" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOQn-lEe6rdachP4tzAw" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOQ3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujYORH-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYORX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYORn-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYOR3-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOSH-lEe6rdachP4tzAw" name="TYPE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOSX-lEe6rdachP4tzAw" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOSn-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujYOS3-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOTH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOTX-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYOTn-lEe6rdachP4tzAw" value="2"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOT3-lEe6rdachP4tzAw" name="NOM_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOUH-lEe6rdachP4tzAw" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOUX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOUn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOU3-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujYOVH-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_ujYOVX-lEe6rdachP4tzAw" name="SYS_C0015451">
        <node defType="com.stambia.rdbms.colref" id="_ujYOVn-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_ujYOV3-lEe6rdachP4tzAw" ref="resource.md#_ujYOLn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_ujYOWH-lEe6rdachP4tzAw" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_ujYOWX-lEe6rdachP4tzAw" ref="resource.md#_ujYOSH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=TYPE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYOWn-lEe6rdachP4tzAw" name="SYS_C0015427">
        <node defType="com.stambia.rdbms.relation" id="_ujYOW3-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYOXH-lEe6rdachP4tzAw" ref="resource.md#_ujYOLn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYOXX-lEe6rdachP4tzAw" ref="resource.md#_ujXmX3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujYOXn-lEe6rdachP4tzAw" name="SYS_C0015428">
        <node defType="com.stambia.rdbms.relation" id="_ujYOX3-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujYOYH-lEe6rdachP4tzAw" ref="resource.md#_ujYOT3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujYOYX-lEe6rdachP4tzAw" ref="resource.md#_ujYNqn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOYn-lEe6rdachP4tzAw" name="ID_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOY3-lEe6rdachP4tzAw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOZH-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujYOZX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujYOZn-lEe6rdachP4tzAw" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujYOZ3-lEe6rdachP4tzAw" name="DATE_IMPORT" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujYOaH-lEe6rdachP4tzAw" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujYOaX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0cH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0cX-lEe6rdachP4tzAw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0cn-lEe6rdachP4tzAw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujY0c3-lEe6rdachP4tzAw" name="SYS_C0015453">
        <node defType="com.stambia.rdbms.relation" id="_ujY0dH-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujY0dX-lEe6rdachP4tzAw" ref="resource.md#_ujYOYn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujY0dn-lEe6rdachP4tzAw" ref="resource.md#_ujY0uH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujY0d3-lEe6rdachP4tzAw" name="SYS_C0015452">
        <node defType="com.stambia.rdbms.relation" id="_ujY0eH-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujY0eX-lEe6rdachP4tzAw" ref="resource.md#_ujYOLn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujY0en-lEe6rdachP4tzAw" ref="resource.md#_ujXmX3-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ujY0e3-lEe6rdachP4tzAw" name="SAS_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ujY0fH-lEe6rdachP4tzAw" value="SAS_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ujY0fX-lEe6rdachP4tzAw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ujY0fn-lEe6rdachP4tzAw" name="CLE_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0f3-lEe6rdachP4tzAw" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0gH-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0gX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0gn-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0g3-lEe6rdachP4tzAw" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujY0hH-lEe6rdachP4tzAw" name="STATUS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0hX-lEe6rdachP4tzAw" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0hn-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujY0h3-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0iH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0iX-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0in-lEe6rdachP4tzAw" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujY0i3-lEe6rdachP4tzAw" name="TYPE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0jH-lEe6rdachP4tzAw" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0jX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujY0jn-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0j3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0kH-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0kX-lEe6rdachP4tzAw" value="3"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujY0kn-lEe6rdachP4tzAw" name="CABINET_RATTACHEMENT" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0k3-lEe6rdachP4tzAw" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0lH-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_ujY0lX-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0ln-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0l3-lEe6rdachP4tzAw" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0mH-lEe6rdachP4tzAw" value="4"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujY0mX-lEe6rdachP4tzAw" name="NOM_FICHIER" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0mn-lEe6rdachP4tzAw" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0m3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0nH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0nX-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0nn-lEe6rdachP4tzAw" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_ujY0n3-lEe6rdachP4tzAw" name="SYS_C0015440">
        <node defType="com.stambia.rdbms.colref" id="_ujY0oH-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_ujY0oX-lEe6rdachP4tzAw" ref="resource.md#_ujY0fn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujY0on-lEe6rdachP4tzAw" name="SYS_C0015416">
        <node defType="com.stambia.rdbms.relation" id="_ujY0o3-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujY0pH-lEe6rdachP4tzAw" ref="resource.md#_ujY0mX-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujY0pX-lEe6rdachP4tzAw" ref="resource.md#_ujYNqn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=NOM_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujY0pn-lEe6rdachP4tzAw" name="ID_FICHIER" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0p3-lEe6rdachP4tzAw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0qH-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0qX-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0qn-lEe6rdachP4tzAw" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujY0q3-lEe6rdachP4tzAw" name="DATE_IMPORT" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0rH-lEe6rdachP4tzAw" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0rX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0rn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0r3-lEe6rdachP4tzAw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0sH-lEe6rdachP4tzAw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ujY0sX-lEe6rdachP4tzAw" name="SYS_C0015441">
        <node defType="com.stambia.rdbms.relation" id="_ujY0sn-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ujY0s3-lEe6rdachP4tzAw" ref="resource.md#_ujY0pn-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ujY0tH-lEe6rdachP4tzAw" ref="resource.md#_ujY0uH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ujY0tX-lEe6rdachP4tzAw" name="SOURCE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ujY0tn-lEe6rdachP4tzAw" value="SOURCE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ujY0t3-lEe6rdachP4tzAw" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_ujY0uH-lEe6rdachP4tzAw" name="ID_FICHIER" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0uX-lEe6rdachP4tzAw" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0un-lEe6rdachP4tzAw" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0u3-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0vH-lEe6rdachP4tzAw" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujY0vX-lEe6rdachP4tzAw" name="NOM_FICHIER" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0vn-lEe6rdachP4tzAw" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0v3-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0wH-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0wX-lEe6rdachP4tzAw" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0wn-lEe6rdachP4tzAw" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_ujY0w3-lEe6rdachP4tzAw" name="DATE_IMPORT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_ujY0xH-lEe6rdachP4tzAw" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_ujY0xX-lEe6rdachP4tzAw" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_ujY0xn-lEe6rdachP4tzAw" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_ujY0x3-lEe6rdachP4tzAw" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_ujY0yH-lEe6rdachP4tzAw" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_ujY0yX-lEe6rdachP4tzAw" name="SYS_C0015439">
        <node defType="com.stambia.rdbms.colref" id="_ujY0yn-lEe6rdachP4tzAw" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_ujY0y3-lEe6rdachP4tzAw" ref="resource.md#_ujY0uH-lEe6rdachP4tzAw?fileId=_ujXmUH-lEe6rdachP4tzAw$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
  </node>
</md:node>