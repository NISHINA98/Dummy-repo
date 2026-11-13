
Area_2
<div class="modal-content">
                    <div id="divDevHead" class="modal-header alert-success">
                        <button type="button" class="close" data-dismiss="modal">×</button>
                        <h4 class="modal-title">Qualitative Assessment</h4>
                    </div>
                    <div class="modal-body">
                        <p>no studies</p>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                    </div>
                </div>

Area 3

<div class="content">

    <div class="box box-info content-panel-position-top">
        <div class="box-header with-border">
            <h3 class="box-title">
                <strong>
                    <span id="cphContent_ctrlAquiferData_lblAquaheading">Technical Databases : Aquifer Data</span>
                </strong>
            </h3>
        </div>
        <!-- /.box-header -->
        <div class="box-body">
            <input type="submit" name="ctl00$cphContent$ctrlAquiferData$btnChangeRegion" value="Button" id="cphContent_ctrlAquiferData_btnChangeRegion" class="hidden">

            <div class="col-lg-12">
                <div class="col-lg-2" style="vertical-align: bottom;">
                    <span id="cphContent_ctrlAquiferData_lblSelectRegion">Select USD Area</span>
                </div>
                <div id="cphContent_ctrlAquiferData_divRegion" class="col-lg-3 area-selection-label" style="display: block; height: 36px; width: 250px; position: absolute; left: 200px;">
                    <input type="hidden" name="ctl00$cphContent$ctrlAquiferData$hdnRegionID" id="cphContent_ctrlAquiferData_hdnRegionID" value="0">
                    <h5>
                        <span id="cphContent_ctrlAquiferData_lblRegion" class="text-danger intput-sm">Area 3</span></h5>
                    
                    <div id="cphContent_ctrlAquiferData_pnlAquaRegion" class="dropdown-menu" style="visibility: hidden; position: absolute; left: 0px; top: 36px; z-index: 1000; display: none;">
		
                        

                        <div id="cphContent_ctrlAquiferData_divUpperShuaibaMap" style="border: 0; overflow: hidden; float: left;">
                            <img id="imgUSDCMap" style="border: 0;" src="../Catalog/ImageHandler.aspx?Path=\\Catalog\\UpperShuaiba\\Upper_Shuaiba_Area_Map.jpg" alt="" usemap="#Map">
                            <map name="Map" id="Map">
                                <area id="Area1" alt="" title="Area 1" target="Area1" onclick="SetAquaRegion(1, 30, event);" datavalue="1" href="#" shape="poly" coords="204,31,370,112,389,118,402,113,418,121,477,108,513,105,569,82,608,55,643,32,205,30">
                                <area id="Area2" alt="" title="Area 2" target="Area2" onclick="SetAquaRegion(2, 30, event);" datavalue="2" href="#" shape="poly" coords="203,76,264,110,283,123,313,140,330,151,348,157,374,160,389,167,401,186,414,195,451,194,485,170,539,151,575,141,654,81,702,32,705,102,620,168,548,210,419,240,358,251,333,243,308,214,260,184,233,144,204,124,202,76">
                                <area id="Area3" alt="" title="Area 3" target="Area3" onclick="SetAquaRegion(3, 30, event);" datavalue="3" href="#" shape="poly" coords="202,128,230,145,253,182,304,214,330,244,361,254,449,239,508,226,585,193,679,126,705,106,705,171,616,263,468,331,412,342,308,324,274,311,247,272,203,240,201,129">
                                <area id="Area4" alt="" title="Area 4" target="Area4" onclick="SetAquaRegion(4, 30, event);" datavalue="4" href="#" shape="poly" coords="203,244,239,270,268,309,401,344,414,346,464,335,547,305,608,278,704,178,706,220,766,219,714,310,589,477,478,563,352,626,203,369,201,244">
                            </map>
                        </div>
                    
	</div>
                </div>
            </div>

            <div class="col-lg-12" style="overflow: auto; min-height: 800px; margin-top: 20px; padding-left: 2px;">
                <div>
		<div id="cphContent_ctrlAquiferData_gvAquiferData_wrapper" class="dataTables_wrapper no-footer"><div class="toolbar"></div><div class="dt-buttons">   <button class="dt-button buttons-copy buttons-html5 fa fa-clipboard" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" type="button"><span> Copy</span></button> <button class="dt-button buttons-print glyphicon glyphicon-print" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" type="button"><span> Print</span></button> </div><div id="cphContent_ctrlAquiferData_gvAquiferData_filter" class="dataTables_filter"><label>Search:<input type="search" class="" placeholder="" aria-controls="cphContent_ctrlAquiferData_gvAquiferData"></label></div><table class="table table-bordered table-hover dataTable no-footer" cellspacing="0" rules="cols" border="1" id="cphContent_ctrlAquiferData_gvAquiferData" style="width: 100%; border-collapse: collapse;" aria-describedby="cphContent_ctrlAquiferData_gvAquiferData_info"><thead><tr class="gridHeaderStyle"><th align="left" scope="col" class="sorting sorting_asc" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-sort="ascending" aria-label="Field: activate to sort column descending" style="width: 41.5px;">Field</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="GDC Region: activate to sort column ascending" style="width: 71.5px;">GDC Region</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Asset: activate to sort column ascending" style="width: 37.5px;">Asset</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Aquifer strength : activate to sort column ascending" style="width: 101.5px;">Aquifer strength </th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Area and or Formation  supported /Aquifer type: activate to sort column ascending" style="width: 287.5px;">Area and or Formation  supported /Aquifer type</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Length (m): activate to sort column ascending" style="width: 68.5px;">Length (m)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Width (m): activate to sort column ascending" style="width: 61.5px;">Width (m)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label=" Height (m): activate to sort column ascending" style="width: 66.5px;"> Height (m)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Radius (m): activate to sort column ascending" style="width: 66.5px;">Radius (m)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Radius In (m): activate to sort column ascending" style="width: 81.5px;">Radius In (m)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Radius Out (m): activate to sort column ascending" style="width: 92.5px;">Radius Out (m)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Enchroachment Angle (degrees): activate to sort column ascending" style="width: 197.5px;">Enchroachment Angle (degrees)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Aquifer Permeability (mD): activate to sort column ascending" style="width: 161.5px;">Aquifer Permeability (mD)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Aquifer Porosity (Fraction): activate to sort column ascending" style="width: 163.5px;">Aquifer Porosity (Fraction)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Total Compressibilty (1/kPa): activate to sort column ascending" style="width: 174.5px;">Total Compressibilty (1/kPa)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Aquifer strength (bbl/psi): activate to sort column ascending" style="width: 156.5px;">Aquifer strength (bbl/psi)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Aquifer response time (days): activate to sort column ascending" style="width: 177.5px;">Aquifer response time (days)</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Aquifer/reservoir ratio: activate to sort column ascending" style="width: 138.5px;">Aquifer/reservoir ratio</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Total Aquifer volume: activate to sort column ascending" style="width: 128.5px;">Total Aquifer volume</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Qualitative Assessment: activate to sort column ascending" style="width: 144.5px;">Qualitative Assessment</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Data Source: activate to sort column ascending" style="width: 74.5px;">Data Source</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Document Number: activate to sort column ascending" style="width: 117.5px;">Document Number</th><th align="left" scope="col" class="sorting" tabindex="0" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" rowspan="1" colspan="1" aria-label="Docment section: activate to sort column ascending" style="width: 103.5px;">Docment section</th></tr></thead>
			<tbody>
		<tr class="odd">
				<td align="left" class="sorting_1">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label2_0">DAFIQ</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label11_0">Area 3</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label10_0">Lekhwair</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label9_0">very week</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label8_0">Limited</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label7_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label6_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label5_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label4_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label3_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label25_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label24_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label23_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label22_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label21_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label20_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label19_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label18_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label13_0"></span>
                            </td><td align="left">

                                <a onclick="return ShowLongText('Qualitative Assessment', this);" id="cphContent_ctrlAquiferData_gvAquiferData_lbtnQualAssess_0" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl02$lbtnQualAssess','')">Reservoir geome</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label17_0" class="hidden">Reservoir geometry is associated with extremely limited aquifer support and waterflooding is therefore a given for this and other Upper Shuaiba developments.  </span>

                            </td><td align="left">
                                <a onclick="return ShowLongText('Data Source', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton2_0" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl02$LinkButton2','')">DAFI-AA&amp;BB 2013</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label14_0" class="hidden">DAFI-AA&amp;BB 2013 FDP</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label15_0"></span>
                            </td><td align="left">
                                <a onclick="return ShowLongText('Docment section', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton1_0" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl02$LinkButton1','')">statment availa</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label16_0" class="hidden">statment available at section 1.1 &amp; 2.8.2</span>
                            </td>
			</tr><tr class="even">
				<td align="left" class="sorting_1">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label2_2">Lekhwair-F</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label11_2">Area 3</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label10_2">Lekhwair</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label9_2">very week</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label8_2">limited</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label7_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label6_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label5_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label4_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label3_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label25_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label24_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label23_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label22_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label21_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label20_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label19_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label18_2"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label13_2"></span>
                            </td><td align="left">

                                <a onclick="return ShowLongText('Qualitative Assessment', this);" id="cphContent_ctrlAquiferData_gvAquiferData_lbtnQualAssess_2" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl04$lbtnQualAssess','')">not mensioned i</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label17_2" class="hidden">not mensioned in 2015 FDP</span>

                            </td><td align="left">
                                <a onclick="return ShowLongText('Data Source', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton2_2" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl04$LinkButton2','')">Lek-F RMS area </a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label14_2" class="hidden">Lek-F RMS area execution FDP</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label15_2">PDO201509100011</span>
                            </td><td align="left">
                                <a onclick="return ShowLongText('Docment section', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton1_2" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl04$LinkButton1','')">na</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label16_2" class="hidden">na</span>
                            </td>
			</tr><tr class="odd">
				<td align="left" class="sorting_1">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label2_1">Malaan</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label11_1">Area 3</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label10_1">Lekhwair</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label9_1">very week</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label8_1">Limited</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label7_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label6_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label5_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label4_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label3_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label25_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label24_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label23_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label22_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label21_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label20_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label19_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label18_1"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label13_1"></span>
                            </td><td align="left">

                                <a onclick="return ShowLongText('Qualitative Assessment', this);" id="cphContent_ctrlAquiferData_gvAquiferData_lbtnQualAssess_1" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl03$lbtnQualAssess','')">The rapid initi</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label17_1" class="hidden">The rapid initial decline in flowing pressure is a consequence of the lack of natural pressure support (no associated aquifer, laterally limited reservoir / linear geometry), (2005 FDP).
Reservoir geometry is seen to be associated with very limited aquifer support and water flooding is therefore the preferred concept for development, (2009 FDP).</span>

                            </td><td align="left">
                                <a onclick="return ShowLongText('Data Source', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton2_1" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl03$LinkButton2','')">MLN-B&amp;C FDP 200</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label14_1" class="hidden">MLN-B&amp;C FDP 2005
MLN-A,B&amp;C FDP 2009
</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label15_1">PDO XD Rpt.Nr. 504
ONPL09092DP</span>
                            </td><td align="left">
                                <a onclick="return ShowLongText('Docment section', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton1_1" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl03$LinkButton1','')">statment availa</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label16_1" class="hidden">statment available at section 1.1 of 2005 &amp; 2009 FDPs</span>
                            </td>
			</tr><tr class="even">
				<td align="left" class="sorting_1">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label2_3">Mazkhour</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label11_3">Area 3</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label10_3">Lekhwair</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label9_3">very week</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label8_3">limited</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label7_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label6_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label5_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label4_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label3_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label25_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label24_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label23_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label22_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label21_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label20_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label19_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label18_3"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label13_3"></span>
                            </td><td align="left">

                                <a onclick="return ShowLongText('Qualitative Assessment', this);" id="cphContent_ctrlAquiferData_gvAquiferData_lbtnQualAssess_3" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl05$lbtnQualAssess','')">not mensioned i</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label17_3" class="hidden">not mensioned in 2015 FDP but commented in the 2012 DSN (there is no aquifer connected to the reservoir.)</span>

                            </td><td align="left">
                                <a onclick="return ShowLongText('Data Source', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton2_3" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl05$LinkButton2','')">MZK RMS area ex</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label14_3" class="hidden">MZK RMS area execution FDP</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label15_3">PDO201606100027</span>
                            </td><td align="left">
                                <a onclick="return ShowLongText('Docment section', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton1_3" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl05$LinkButton1','')">na</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label16_3" class="hidden">na</span>
                            </td>
			</tr></tbody></table><div class="dataTables_info" id="cphContent_ctrlAquiferData_gvAquiferData_info" role="status" aria-live="polite">Showing 1 to 4 of 4 entries</div><div class="dataTables_paginate paging_full_numbers" id="cphContent_ctrlAquiferData_gvAquiferData_paginate"><a class="paginate_button first disabled" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" data-dt-idx="0" tabindex="-1" id="cphContent_ctrlAquiferData_gvAquiferData_first">First</a><a class="paginate_button previous disabled" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" data-dt-idx="1" tabindex="-1" id="cphContent_ctrlAquiferData_gvAquiferData_previous">Previous</a><span><a class="paginate_button current" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" data-dt-idx="2" tabindex="0">1</a></span><a class="paginate_button next disabled" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" data-dt-idx="3" tabindex="-1" id="cphContent_ctrlAquiferData_gvAquiferData_next">Next</a><a class="paginate_button last disabled" aria-controls="cphContent_ctrlAquiferData_gvAquiferData" data-dt-idx="4" tabindex="-1" id="cphContent_ctrlAquiferData_gvAquiferData_last">Last</a></div></div>
	</div>

            </div>
        </div>
        <!-- /.box-body -->
    </div>
</div>

<div class="modal-content">
                    <div id="divDevHead" class="modal-header alert-success">
                        <button type="button" class="close" data-dismiss="modal">×</button>
                        <h4 class="modal-title">Qualitative Assessment</h4>
                    </div>
                    <div class="modal-body">
                        <p>Reservoir geometry is associated with extremely limited aquifer support and waterflooding is therefore a given for this and other Upper Shuaiba developments.  </p>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                    </div>
                </div>



                <div class="modal-content">
                    <div id="divDevHead" class="modal-header alert-success">
                        <button type="button" class="close" data-dismiss="modal">×</button>
                        <h4 class="modal-title">Qualitative Assessment</h4>
                    </div>
                    <div class="modal-body">
                        <p>not mensioned in 2015 FDP</p>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                    </div>
                </div><div class="modal-content">
                    <div id="divDevHead" class="modal-header alert-success">
                        <button type="button" class="close" data-dismiss="modal">×</button>
                        <h4 class="modal-title">Qualitative Assessment</h4>
                    </div>
                    <div class="modal-body">
                        <p>The rapid initial decline in flowing pressure is a consequence of the lack of natural pressure support (no associated aquifer, laterally limited reservoir / linear geometry), (2005 FDP).
Reservoir geometry is seen to be associated with very limited aquifer support and water flooding is therefore the preferred concept for development, (2009 FDP).</p>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                    </div>
                </div><div class="modal-content">
                    <div id="divDevHead" class="modal-header alert-success">
                        <button type="button" class="close" data-dismiss="modal">×</button>
                        <h4 class="modal-title">Qualitative Assessment</h4>
                    </div>
                    <div class="modal-body">
                        <p>not mensioned in 2015 FDP but commented in the 2012 DSN (there is no aquifer connected to the reservoir.)</p>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                    </div>
                </div>




area 4
<div class="content">

    <div class="box box-info content-panel-position-top">
        <div class="box-header with-border">
            <h3 class="box-title">
                <strong>
                    <span id="cphContent_ctrlAquiferData_lblAquaheading">Technical Databases : Aquifer Data</span>
                </strong>
            </h3>
        </div>
        <!-- /.box-header -->
        <div class="box-body">
            <input type="submit" name="ctl00$cphContent$ctrlAquiferData$btnChangeRegion" value="Button" id="cphContent_ctrlAquiferData_btnChangeRegion" class="hidden">

            <div class="col-lg-12">
                <div class="col-lg-2" style="vertical-align: bottom;">
                    <span id="cphContent_ctrlAquiferData_lblSelectRegion">Select USD Area</span>
                </div>
                <div id="cphContent_ctrlAquiferData_divRegion" class="col-lg-3 area-selection-label" style="display: block; height: 36px; width: 250px; position: absolute; left: 200px;">
                    <input type="hidden" name="ctl00$cphContent$ctrlAquiferData$hdnRegionID" id="cphContent_ctrlAquiferData_hdnRegionID" value="0">
                    <h5>
                        <span id="cphContent_ctrlAquiferData_lblRegion" class="text-danger intput-sm">Area 4</span></h5>
                    
                    <div id="cphContent_ctrlAquiferData_pnlAquaRegion" class="dropdown-menu" style="display: none; visibility: hidden; position: absolute;">
		
                        

                        <div id="cphContent_ctrlAquiferData_divUpperShuaibaMap" style="border: 0; overflow: hidden; float: left;">
                            <img id="imgUSDCMap" style="border: 0;" src="../Catalog/ImageHandler.aspx?Path=\\Catalog\\UpperShuaiba\\Upper_Shuaiba_Area_Map.jpg" alt="" usemap="#Map">
                            <map name="Map" id="Map">
                                <area id="Area1" alt="" title="Area 1" target="Area1" onclick="SetAquaRegion(1, 30, event);" datavalue="1" href="#" shape="poly" coords="204,31,370,112,389,118,402,113,418,121,477,108,513,105,569,82,608,55,643,32,205,30">
                                <area id="Area2" alt="" title="Area 2" target="Area2" onclick="SetAquaRegion(2, 30, event);" datavalue="2" href="#" shape="poly" coords="203,76,264,110,283,123,313,140,330,151,348,157,374,160,389,167,401,186,414,195,451,194,485,170,539,151,575,141,654,81,702,32,705,102,620,168,548,210,419,240,358,251,333,243,308,214,260,184,233,144,204,124,202,76">
                                <area id="Area3" alt="" title="Area 3" target="Area3" onclick="SetAquaRegion(3, 30, event);" datavalue="3" href="#" shape="poly" coords="202,128,230,145,253,182,304,214,330,244,361,254,449,239,508,226,585,193,679,126,705,106,705,171,616,263,468,331,412,342,308,324,274,311,247,272,203,240,201,129">
                                <area id="Area4" alt="" title="Area 4" target="Area4" onclick="SetAquaRegion(4, 30, event);" datavalue="4" href="#" shape="poly" coords="203,244,239,270,268,309,401,344,414,346,464,335,547,305,608,278,704,178,706,220,766,219,714,310,589,477,478,563,352,626,203,369,201,244">
                            </map>
                        </div>
                    
	</div>
                </div>
            </div>

            <div class="col-lg-12" style="overflow: auto; min-height: 800px; margin-top: 20px; padding-left: 2px;">
                <div>
		<table class="table table-bordered table-hover" cellspacing="0" rules="cols" border="1" id="cphContent_ctrlAquiferData_gvAquiferData" style="width:100%;border-collapse:collapse;">
			<tbody><tr class="gridHeaderStyle">
				<th align="left" scope="col">Field</th><th align="left" scope="col">GDC Region</th><th align="left" scope="col">Asset</th><th align="left" scope="col">Aquifer strength </th><th align="left" scope="col">Area and or Formation  supported /Aquifer type</th><th align="left" scope="col">Length (m)</th><th align="left" scope="col">Width (m)</th><th align="left" scope="col"> Height (m)</th><th align="left" scope="col">Radius (m)</th><th align="left" scope="col">Radius In (m)</th><th align="left" scope="col">Radius Out (m)</th><th align="left" scope="col">Enchroachment Angle (degrees)</th><th align="left" scope="col">Aquifer Permeability (mD)</th><th align="left" scope="col">Aquifer Porosity (Fraction)</th><th align="left" scope="col">Total Compressibilty (1/kPa)</th><th align="left" scope="col">Aquifer strength (bbl/psi)</th><th align="left" scope="col">Aquifer response time (days)</th><th align="left" scope="col">Aquifer/reservoir ratio</th><th align="left" scope="col">Total Aquifer volume</th><th align="left" scope="col">Qualitative Assessment</th><th align="left" scope="col">Data Source</th><th align="left" scope="col">Document Number</th><th align="left" scope="col">Docment section</th>
			</tr><tr>
				<td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label2_0">Dhulaima</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label11_0">Area 4</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label10_0">Lekhwair</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label9_0">very week</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label8_0">limited</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label7_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label6_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label5_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label4_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label3_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label25_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label24_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label23_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label22_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label21_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label20_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label19_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label18_0"></span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label13_0"></span>
                            </td><td align="left">

                                <a onclick="return ShowLongText('Qualitative Assessment', this);" id="cphContent_ctrlAquiferData_gvAquiferData_lbtnQualAssess_0" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl02$lbtnQualAssess','')">DSN 2014 did no</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label17_0" class="hidden">DSN 2014 did not mention</span>

                            </td><td align="left">
                                <a onclick="return ShowLongText('Data Source', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton2_0" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl02$LinkButton2','')">DM 2014 DSN</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label14_0" class="hidden">DM 2014 DSN</span>
                            </td><td align="left">
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label15_0">EXP2014-0152</span>
                            </td><td align="left">
                                <a onclick="return ShowLongText('Docment section', this);" id="cphContent_ctrlAquiferData_gvAquiferData_LinkButton1_0" href="javascript:__doPostBack('ctl00$cphContent$ctrlAquiferData$gvAquiferData$ctl02$LinkButton1','')">na</a>
                                <span id="cphContent_ctrlAquiferData_gvAquiferData_Label16_0" class="hidden">na</span>
                            </td>
			</tr>
		</tbody></table>
	</div>

            </div>
        </div>
        <!-- /.box-body -->
    </div>
</div>
