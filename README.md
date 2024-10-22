<Configuration>
    <com.dts.freefireth>
        <!-- ANTDETECT configuration -->
        <ANTDETECT>
            <!-- Update script -->
            <!-- Works on all devices and all Android versions -->
            <mconfig.antibanned.file>
                ~antibanned.config
                ~feature.antibanned
                ~anticheat.ff
                <configuration.antibanned.file>
                    ~antibanned.script
                </configuration.antibanned.file>
            </mconfig.antibanned.file>

            <blocks>
                <block name="AJAX config sections"/>
                <block name="AJAX controls registration"/>
                <block name="AJAX compilation"/>
                <block name="AJAX HTTP handlers"/>
                <block name="AJAX HTTP modules"/>
                <block name="AJAX system.web.extensions"/>
                <block name="AJAX system.webServer"/>
                <block name="DynamicData controls registration"/>
                <block name="DynamicData compilation"/>
                <block name="DynamicData HTTP modules"/>
            </blocks>

            <feature name="ANTDETECT" target="account">
                <description><![CDATA[
                    Adds entries to your Web.config file which are required by any .NET 3.5 AJAX.NET application.
                ]]></description>
                <blocks>
                    <block name="ANTDETECT config sections"/>
                </blocks>
            </feature>
        </ANTDETECT>

        <!-- Anti Banned configuration -->
        <AntiBanned>
            <mconfig.antibanned.file>
                ~antibanned.config
                ~feature.antibanned
                ~anticheat.ff
                <configuration.antibanned.file>
                    ~antibanned.script
                </configuration.antibanned.file>
            </mconfig.antibanned.file>

            <blocks>
                <block name="AJAX config sections"/>
                <block name="AJAX controls registration"/>
                <block name="AJAX compilation"/>
                <block name="AJAX HTTP handlers"/>
                <block name="AJAX HTTP modules"/>
                <block name="AJAX system.web.extensions"/>
                <block name="AJAX system.webServer"/>
                <block name="DynamicData controls registration"/>
                <block name="DynamicData compilation"/>
                <block name="DynamicData HTTP modules"/>
            </blocks>

            <feature name="ANTI BANNED" target="account">
                <description><![CDATA[
                    Adds entries to your Web.config file which are required by any .NET 3.5 AJAX.NET application.
                ]]></description>
                <blocks>
                    <block name="ANTI BANNED config sections"/>
                </blocks>
            </feature>
        </AntiBanned>

        <!-- Aim Bot configuration -->
        <AimBot>
            <enabled>true</enabled>
            <accuracy>100%</accuracy>
            <description><![CDATA[
                Aimbot feature for achieving perfect aim accuracy.
            ]]></description>
        </AimBot>

        <!-- Aim Look configuration -->
        <AimLook>
            <enabled>true</enabled>
            <accuracy>100%</accuracy>
            <description><![CDATA[
                Aim Look feature for perfect targeting.
            ]]></description>
        </AimLook>

        <!-- No Recoil configuration -->
        <NoRecoil>
            <enabled>true</enabled>
            <description><![CDATA[
                Ensures no recoil while shooting.
            ]]></description>
        </NoRecoil>

        <!-- TXT Setting View configuration -->
        <TXT_SETTING_VIEW>
            <blocks>
                <block name="AJAX config sections"/>
                <block name="AJAX controls registration"/>
                <block name="AJAX compilation"/>
                <block name="AJAX HTTP handlers"/>
                <block name="AJAX HTTP modules"/>
                <block name="AJAX system.web.extensions"/>
                <block name="AJAX system.webServer"/>
                <block name="DynamicData controls registration"/>
                <block name="DynamicData compilation"/>
                <block name="DynamicData HTTP modules"/>
            </blocks>

            <feature name="TXT_SETTING_VIEW" target="account">
                <description><![CDATA[
                    Adds entries to your Web.config file which are required by any .NET 3.5 AJAX.NET application.
                ]]></description>
                <blocks>
                    <block name="TXT_SETTING_VIEW config sections"/>
                </blocks>
            </feature>
        </TXT_SETTING_VIEW>
    </com.dts.freefireth>
</Configuration>
