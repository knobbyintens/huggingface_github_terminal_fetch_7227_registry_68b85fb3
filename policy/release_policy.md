# Release License Policy (v3.4)

Scope: all public dataset releases registered in this repository.

1. Every released artifact declares exactly one license identifier.

2. A single-source artifact is released under that source's license.

3. A multi-source artifact is released under the source license that is most
   permissive for derivative works and secondary use.

4. "Most permissive for derivative works and secondary use" means the license
   that imposes the fewest restrictions on downstream redistribution,
   adaptation (including the creation of derivative datasets), and commercial
   reuse. The following count as restrictions that narrow downstream freedom:
   mandatory propagation of the source license to derivative works; a
   requirement that downstream users accept an additional acceptable-use
   policy; field-of-use or territorial limits; thresholds that trigger extra
   licensing; and any other condition that narrows what a downstream user may
   do. Attribution and notice requirements alone do not make a license less
   permissive.

5. License tags shown on public hubs are metadata, not terms of use. A tag of
   `other` is not a license and must never be copied into a manifest as if it
   were one. Resolve opaque tags by reading the full license text shipped with
   the source, and evaluate all clauses, including clauses that address
   derivative works and the ownership or permitted use of outputs. Do not rely
   on repository names, download counts, or third-party summaries.

6. The declared identifier is the lower-case identifier shown in the upstream
   source's license metadata (for example `apache-2.0` or `odc-by`), without a
   version suffix unless the metadata itself includes one.

7. Publication procedure: write the release manifest to
   `releases/<release_id>/manifest.json`, and open an issue titled
   `Release license declaration - <release_id>` whose body lists one line per
   artifact in the form `<artifact-name>: <license identifier>`.
