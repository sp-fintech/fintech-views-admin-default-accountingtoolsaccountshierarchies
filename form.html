{% if hierarchy['id'] is defined %}
    {% set hierarchyId = hierarchy['id'] %}
    {% set hierarchyName = hierarchy['name'] %}
    {% set hierarchyDescription = hierarchy['description'] %}
    {% set hierarchyHierarchy = hierarchy['hierarchy'] %}
{% else %}
    {% set hierarchyId = '' %}
    {% set hierarchyName = '' %}
    {% set hierarchyDescription = '' %}
    {% set hierarchyHierarchy = '' %}
{% endif %}
<form data-validateon="section" id="{{componentId}}-{{sectionId}}-form">
    <fieldset id="{{componentId}}-{{sectionId}}-fieldset">
        <div class="row">
            <div class="col">
                {{adminltetags.useTag('fields',
                    [
                        'component'                      : component,
                        'componentName'                  : componentName,
                        'componentId'                    : componentId,
                        'sectionId'                      : sectionId,
                        'fieldId'                        : 'id',
                        'fieldLabel'                     : 'ID',
                        'fieldType'                      : 'input',
                        'fieldHelp'                      : true,
                        'fieldHelpTooltipContent'        : 'ID',
                        'fieldRequired'                  : true,
                        'fieldBazScan'                   : true,
                        'fieldBazPostOnCreate'           : false,
                        'fieldBazPostOnUpdate'           : true,
                        'fieldHidden'                    : true,
                        'fieldDisabled'                  : true,
                        'fieldValue'                     : hierarchyId
                    ]
                )}}
            </div>
        </div>
        <div class="row">
            <div class="col">
                {{adminltetags.useTag('fields',
                    [
                        'component'                      : component,
                        'componentName'                  : componentName,
                        'componentId'                    : componentId,
                        'sectionId'                      : sectionId,
                        'fieldId'                        : 'name',
                        'fieldLabel'                     : 'Name',
                        'fieldType'                      : 'input',
                        'fieldHelp'                      : true,
                        'fieldHelpTooltipContent'        : 'Name',
                        'fieldRequired'                  : true,
                        'fieldBazScan'                   : true,
                        'fieldBazJstreeSearch'           : true,
                        'fieldBazPostOnCreate'           : true,
                        'fieldBazPostOnUpdate'           : true,
                        'fieldDataInputMinLength'        : 1,
                        'fieldDataInputMaxLength'        : 50,
                        'fieldValue'                     : hierarchyName
                    ]
                )}}
            </div>
        </div>
        <div class="row">
            <div class="col">
                {{adminltetags.useTag('fields',
                    [
                        'component'                      : component,
                        'componentName'                  : componentName,
                        'componentId'                    : componentId,
                        'sectionId'                      : sectionId,
                        'fieldId'                        : 'description',
                        'fieldLabel'                     : 'Description',
                        'fieldType'                      : 'textarea',
                        'fieldDataMaxLength'             : 4096,
                        'fieldHelp'                      : true,
                        'fieldHelpTooltipContent'        : 'Description of the hierarchy',
                        'fieldRequired'                  : false,
                        'fieldBazScan'                   : true,
                        'fieldBazJstreeSearch'           : true,
                        'fieldBazPostOnCreate'           : true,
                        'fieldBazPostOnUpdate'           : true,
                        'fieldDataInputMaxLength'        : 1024,
                        'fieldTextareaRows'              : 2,
                        'fieldValue'                     : hierarchyDescription
                    ]
                )}}
            </div>
        </div>
        {% include '/accountshierarchies/builder.html' %}
        <div class="row">
            <div class="col">
                {{adminltetags.useTag('fields',
                    [
                        'component'                      : component,
                        'componentName'                  : componentName,
                        'componentId'                    : componentId,
                        'sectionId'                      : sectionId,
                        'fieldId'                        : 'hierarchy',
                        'fieldLabel'                     : 'Hierarchy',
                        'fieldType'                      : 'textarea',
                        'fieldDataMaxLength'             : 4096,
                        'fieldHelp'                      : true,
                        'fieldHelpTooltipContent'        : 'Hierarchy',
                        'fieldRequired'                  : true,
                        'fieldBazScan'                   : true,
                        'fieldBazJstreeSearch'           : true,
                        'fieldBazPostOnCreate'           : true,
                        'fieldBazPostOnUpdate'           : true,
                        'fieldDataInputMaxLength'        : 65535,
                        'fieldTextareaRows'              : 8,
                        'fieldValue'                     : hierarchyHierarchy
                    ]
                )}}
            </div>
        </div>
    </fieldset>
</form>
<script>
/*global paginatedPNotify BazProgress BazContentFields BazHelpers BazContentLoader Pace BazCore dataCollection Swal */
var dataCollectionComponent, dataCollectionSection, dataCollectionSectionForm;

if (!window['dataCollection']['{{componentId}}']) {
    dataCollectionComponent =
        window['dataCollection']['{{componentId}}'] = { };
} else {
    dataCollectionComponent =
        window['dataCollection']['{{componentId}}'];
}
if (!dataCollectionComponent['{{componentId}}-{{sectionId}}']) {
    dataCollectionSection =
        dataCollectionComponent['{{componentId}}-{{sectionId}}'] = { };
} else {
    dataCollectionSection =
        dataCollectionComponent['{{componentId}}-{{sectionId}}'];
}
if (!dataCollectionSection['{{componentId}}-{{sectionId}}-form']) {
    dataCollectionSectionForm =
        dataCollectionSection['{{componentId}}-{{sectionId}}-form'] = { };
} else {
    dataCollectionSectionForm =
        dataCollectionSection['{{componentId}}-{{sectionId}}-form'];
}

dataCollectionSection =
    $.extend(dataCollectionSection, {
        '{{componentId}}-{{sectionId}}-id'                    : { },
        '{{componentId}}-{{sectionId}}-name'                  : { },
        '{{componentId}}-{{sectionId}}-description'           : { },
        '{{componentId}}-{{sectionId}}-hierarchy'             : { },
        '{{componentId}}-{{sectionId}}-form' : {
            rules: {
                '{{componentId}}-{{sectionId}}-name'          : 'required',
                '{{componentId}}-{{sectionId}}-hierarchy'     : 'required'
            },
            messages: {
                '{{componentId}}-{{sectionId}}-name'          : 'Please enter name',
                '{{componentId}}-{{sectionId}}-hierarchy'     : 'Please enter hierarchy'
            }
        }
});
</script>