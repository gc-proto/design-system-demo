---
altLangPage: https://www.canada.ca/fr/gouvernement/a-propos/systeme-conception/bibliotheque-modeles.html
date: 2021-05-03
dateModified: 2019-11-28
description: Templates and patterns for Canada.ca.
permalink: en/pattern-library.html
title: Template and pattern library for Canada.ca
---
<p class="gc-byline"><strong>From <a href="https://www.canada.ca/en/treasury-board-secretariat.html">Treasury Board of Canada Secretariat</a></strong></p>
<p>These patterns and page layouts have been user-tested. They were designed to help you develop digital content focused on the task people are trying to accomplish.</p>
<a href="https://www.canada.ca/en/government/about/design-system/pattern-library/find-right-template-design-pattern-web-content.html" class="btn btn-default mrgn-bttm-md">Answer a few questions to find the right pattern</a>
<h2>All templates and patterns</h2>
<div class="row mrgn-tp-md">
  <div class="col-md-3">
    <details open="">
      <summary class="btn btn-primary">Filter options</summary>
      <p class="mrgn-tp-md">Use these filters to find templates and patterns.</p>
      <form class="wb-tables-filter mrgn-lft-md mrgn-rght-md" data-bind-to="dataset-filter">
        <div class="row">
          <div class="form-group">
            <label for="dt_cat">Pattern, template or style</label>
            <select class="form-control maxwidth" id="dt_cat" name="dt_cat" data-column="2">
              <option value="">All</option>
              <option value="Design pattern">Design patterns</option>
              <option value="Template">Template</option>
              <option value="Style">Style</option>
            </select>
          </div>
          <div class="form-group">
            <label for="dt_type">Types</label>
            <select class="form-control maxwidth" id="dt_type" name="dt_type" data-column="3">
              <option value="">All</option>
              <option value="Destination">Destination</option>
              <option value="Government-wide template">Government-wide</option>
              <option value="Institutional">Institutional</option>
              <option value="Interaction">Interaction</option>
              <option value="Navigation">Navigation</option>
              <option value="Promotion">Promotional</option>
              <option value="Site">Site-wide</option>
              <option value="Theme template">Theme and topic</option>
              <option value="Visual">Visual</option>
            </select>
          </div>
          <div class="form-group">
            <label for="dt_mand">Mandatory or suggested</label>
            <select class="form-control maxwidth" id="dt_mand" name="dt_mand" data-column="4">
            <option value="">All</option>
            <option value="Mandatory">Mandatory</option>
            <option value="No">Suggested</option>
            </select>
          </div>
          <div class="col-md-6">
            <button type="submit" class="btn btn-primary" aria-controls="dataset-filter">Filter</button>
          </div>
          <div class="col-md-6">
            <button type="reset" class="btn btn-default">Clear</button>
          </div>
        </div>
      </form>
    </details>
  </div>
  <div class="col-md-9 small">
    <div id="dataset-filter_wrapper" class="dataTables_wrapper no-footer">
    <div class="top">
    <div id="dataset-filter_filter" class="dataTables_filter">
      <label>Filter items
        <input class="" type="search" placeholder="" aria-controls="dataset-filter">
      </label>
    </div>
    <div class="dataTables_info" id="dataset-filter_info" role="status" aria-live="polite">Showing 1 to 72 of 72 entries</div>
    <div class="dataTables_length" id="dataset-filter_length">
      <label>Show
        <select class="" aria-controls="dataset-filter" name="dataset-filter_length">
        <option value="10">10</option>
        <option value="25">25</option>
        <option value="50">50</option>
        <option value="100">100</option>
        </select> entries
      </label>
    </div>
  </div>
  <table
    class="wb-tables table table-striped dataTable no-footer"
    id="dataset-filter"
    aria-live="polite"
    data-wb-tables='{
      "iDisplayLength": 100,
      "bDeferRender": true,
      "ajaxSource": "https://design.canada.ca/ajax/patterns.json",
      "order": [0, "asc"],
      "columns": [
        { "data": "NAME", "className": "nws-tbl-name h4" },
        { "data": "USE", "className": "nws-tbl-use" },
        { "data": "CAT", "className": "nws-tbl-cat" },
        { "data": "TYPE", "className": "nws-tbl-type" },
        { "data": "MANDATORY", "visible": false }
      ]}'
    aria-describedby="dataset-filter_info"
    style="width: 850px;"
    aria-label="This table provides a sorting feature via the buttons across the column header row with only one instance visible at a time.">
    <thead>
      <tr>
        <th>Name</th>
        <th>When to use this pattern</th>
        <th>Category</th>
        <th>Type</th>
        <th>Mandatory</th>
      </tr>
    </thead>
  </table>
</div>
