# windows-10
<Configuration ID="21b120c9-0bed-4412-8e90-b91761373ff9">
  <Add OfficeClientEdition="64" Channel="PerpetualVL2021" OfficeMgmtCOM="TRUE" MigrateArch="TRUE">
    <Product ID="ProPlusSPLA2021Online Key" PIDKEY="B4NPR-3FKK7-T2MBV-FRQ4W-PKD89">
      <Language ID="en-us" />
      <Language ID="ar-sa" />
      <Language ID="MatchPreviousMSI" />
      <ExcludeApp ID="Groove" />
      <ExcludeApp ID="Lync" />
    </Product>
    <Product ID="VisioPro2019Online Key" PIDKEY="9BGNQ-K37YR-RQHF2-38RQ3-7VCBB">
      <Language ID="en-us" />
      <Language ID="ar-sa" />
      <Language ID="MatchPreviousMSI" />
      <ExcludeApp ID="Groove" />
      <ExcludeApp ID="Lync" />
    </Product>
    <Product ID="ProjectPro2021Online Key" PIDKEY="FTNWT-C6WBT-8HMGF-K9PRX-QV9H8">
      <Language ID="en-us" />
      <Language ID="ar-sa" />
      <Language ID="MatchPreviousMSI" />
      <ExcludeApp ID="Groove" />
      <ExcludeApp ID="Lync" />
    </Product>
    <Product ID="LanguagePack">
      <Language ID="en-us" />
      <Language ID="ar-sa" />
      <Language ID="MatchPreviousMSI" />
    </Product>
    <Product ID="ProofingTools">
      <Language ID="id-id" />
    </Product>
  </Add>
  <Property Name="SharedComputerLicensing" Value="1000" />
  <Property Name="FORCEAPPSHUTDOWN" Value="FALSE" />
  <Property Name="DeviceBasedLicensing" Value="1000" />
  <Property Name="SCLCacheOverride" Value="1000" />
  <Property Name="TenantId" Value="e5b86b07-841e-492f-9e77-971538aa7fdc" />
  <Property Name="AUTOACTIVATE" Value="1000" />
  <RemoveMSI />
  <AppSettings>
    <Setup Name="Company" Value="office" />
    <User Key="software\microsoft\office\16.0\excel\options" Name="defaultformat" Value="60" Type="REG_DWORD" App="excel16" Id="L_SaveExcelfilesas" />
    <User Key="software\microsoft\office\16.0\powerpoint\options" Name="defaultformat" Value="52" Type="REG_DWORD" App="ppt16" Id="L_SavePowerPointfilesas" />
    <User Key="software\microsoft\office\16.0\word\options" Name="defaultformat" Value="ODT" Type="REG_SZ" App="word16" Id="L_SaveWordfilesas" />
  </AppSettings>
  <Display Level="Full" AcceptEULA="TRUE" />
</Configuration>
